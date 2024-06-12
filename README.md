 # 32bit_processor
 The above is the 32bit RISC implementation of a MIPS architecture based processor.
 It works on the principle of pipelining where are five stages of execution IF,ID,EX,MEM,WB stages.
 IF stage stands for the instruction fetch ,ID stage is stage where instruction is decoded,Ex stage helps to execute the operation on the instruction based on the opcode,Mem stage stores the instrucution to memory and Wb stage is to wite back the calculated register value to the memory.
 The above repository contains the code for RISC 32 bit processor with file name MIPS32_microprocessor.v . It is verilog implemented file. 
 The test_mipss32.v is the corresponding testbench in which i have given different operations and operands.
