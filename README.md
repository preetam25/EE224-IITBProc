# EE224-IITBProc
EE224 Digital Design Course Project

List of components-

ARITHEMATIC UNIT
adder16.vhdl: 16-bit adder
nandbit.vhdl: 16-bitwise NAND
alu.vhdl: combination of ADD and NAND with flag registers(C,Z flags)

MULTIPLEXERS
1-bit
Mux1_2_1.vhdl: 2-to-1 MUX
Mux1_4_1.vhdl: 4-to-1 MUX
3-bit
Mux3_2_1.vhdl: 2-to-1 MUX
Mux3_4_1.vhdl: 4-to-1 MUX
16-bit
Mux16_2_1.vhdl: 2-to-1 MUX
Mux16_4_1.vhdl: 4-to-1 MUX

REGISTERS
Register1.vhdl: 1-bit register with synchronous write and ascynchonous read
Register16.vhdl: 16-bit register with synchronous write and ascynchonous read
Register_file.vhdl: Set of 8 16-bit registers

MEMORY UNIT
Memory_asyncread_syncwrite.vhd

FSM
FSM.vhdl: Controller FSM (controls signals)

DUT
iitb_proc.vhdl: Main code
