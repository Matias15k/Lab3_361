# RISC-V CPU (RV32I, RV32M)

Developed by Zach Tey, Matias Ketema

To run tests-> (for pipelined version)

Method 1: run_tests.sh script
1) Add <name>_mem_in.hex and <name>_regs_in.hex file into 'tests' folder
2) Add <name> into run_tests.sh (line 13) eg. tests=("lui" "easy")
3) Run "./run_tests.sh

Method 2: Makefile
1) Add <name>_mem_in.hex and <name>_regs_in.hex file into 'tests' folder
2) Add <name> into Makfile (line 8) eg. TESTS = lui
3) Run "make run_all", or "make run TEST=<name>"