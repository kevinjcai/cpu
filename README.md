# CS61CPU

Look ma, I made a CPU! Here's what I did:
The Cpu can run RISCV instructions with a two stage pipeline to increase the speed of computation. It can support multiple instructions like loading and storing to memory, adding two registors, and performing logical operations. The pipeline was used so it can perform different operations at different timesteps allowing it to have parrlel operations increasing the processing speed of the cpu. It can run I-Type, B-Type, R-Type, S-Type, U-Type, and J-Type functions. The CPU stores the PC and the instruction for a particular cycle and allows the program to run different portions of the code at the same time because some sections are seperated allowing them to run independently from each other if they have the proper instructions that will allow for pipelining. 
-
