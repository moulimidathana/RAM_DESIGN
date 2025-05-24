# RAM_DESIGN
*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : MIDATHANA MOULI

*INTERN ID* : CT06DN38

*DOMAIN* :  VLSI

*DURATION* : 6 WEEKS

*MENTOR* : NEELA SANTOSH

## I have successfully completed the design and implementation of a 16 x 8-bit synchronous RAM module using Verilog HDL. The RAM is designed to perform both read and write operations based on control signals, and its behavior is governed by the rising edge of a clock signal (clk). The memory module contains 16 locations, each capable of storing 8-bit data. This means the module can store up to 128 bits (16 × 8) of information in total. The address lines used are 4 bits wide ([3:0] addr), which provides access to 16 distinct memory locations (from address 0 to 15), while the data lines (din and dout) are 8 bits wide, supporting byte-level operations.

## To gain conceptual clarity before writing the code, I referred to the NPTEL video lectures by Prof. Indranil Sengupta, which provided an excellent theoretical background on synchronous memory operations and digital design. After grasping the core principles, I proceeded to write the Verilog code independently. During the development and testing phases, I utilized ChatGPT to rectify syntax and logical errors in the testbench and to ensure correct alignment of read and write operations with the clock signal.

## In this design, the write operation is performed when the write enable (wr) signal is high, and the read operation is executed when the read enable (rd) signal is high. Both operations are synchronized with the positive edge of the clock to ensure predictable behavior in digital systems, which is a standard practice in synchronous design.

## To verify the correctness of the RAM module, I created a testbench where I initialized all control signals and simulated the behavior over time. The testbench includes a clock generator that toggles the clock every 10 nanoseconds, providing a 20 ns clock period. I tested the RAM by performing a write operation at address 2 with the data 11001010 (in binary), followed by a read operation from the same address to confirm that the data was correctly stored and retrieved. Similarly, I performed another write operation at address 5 with data 10101011, followed again by a read from address 5 to verify the successful execution.

## The testbench is carefully structured to allow sufficient time between setting the control signals and the clock edges to ensure that the data is latched or read properly. The results showed that the memory module behaves exactly as expected, demonstrating correct storage and retrieval of 8-bit data from specific memory addresses.

## This project has enhanced my understanding of memory design in digital systems, especially regarding control signal timing, synchronization, and testbench simulation. It also provided valuable experience in debugging and waveform analysis using simulation tools. The design serves as a foundational step for more advanced digital systems such as dual-port RAM, FIFOs, or memory-mapped I/O in embedded systems.

## In conclusion, this 16 x 8-bit synchronous RAM module is a compact yet powerful example of how memory blocks are designed and tested using hardware description languages. The combination of theoretical learning and practical implementation has strengthened my knowledge in digital design and HDL programming. 


# OUTPUT :

![Image](https://github.com/user-attachments/assets/77bced40-0ab8-4dc8-bc4c-cd4941995eab)



![Image](https://github.com/user-attachments/assets/a19ca47b-c85d-4a69-8d2f-183f795bc3aa)


