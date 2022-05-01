## Data Encryption Standard Algorithm Code Breaker

### About this project:

The Data Encryption Standard algorithm is a method for encrypting and decrypting data. It was once widely used to protect data, but has since been replaced with the more complex Advanced Encyrption Standard algorithm. Click [here](https://page.math.tu-berlin.de/~kant/teaching/hess/krypto-ws2006/des.htm) to learn more about the Data Encyrption Standard algorithm. 

The Data Encryption Standard is no longer in use due to the lack of the difficulty it takes to crack the key with a sequential number counter. This code serves as a general purpose code breaker applied to the DES algorithm. Given a known text and ciphertext, a counter that increments indefinitely can serve as a possible key that will increment up until the correct key is found. 

This code was written in System Verilog to be uploaded to a Xilinx FPGA as the final project for [Dr. Stine's](https://experts.okstate.edu/james.stine) Digital Logic Design class at [Oklahoma State University](https://go.okstate.edu/). Go Pokes!

Datapath diagram (Credit: Dr. Stine):
![Datapath diagram (Credit Dr. Stine)](https://github.com/TylerGraham74/DLD-DES-Code-Breaker/blob/gh-pages/Screen%20Shot%202022-04-29%20at%202.16.34%20PM.png?raw=true) 
 
Cracker finding the correct key:
![Cracker finding the correct key](https://github.com/TylerGraham74/DLD-DES-Code-Breaker/blob/gh-pages/image6.png?raw=true)

Xilinx FPGA Implementation:
![Xilinx FPGA Implementation](https://github.com/TylerGraham74/DLD-DES-Code-Breaker/blob/gh-pages/image5.jpg?raw=true)

