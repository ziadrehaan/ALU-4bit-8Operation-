# ALU 4bit - 8 Operations

![Demo](https://sdmntprsouthcentralus.oaiusercontent.com/files/00000000-a8f4-61f7-9493-ef3207bbcc05/raw?se=2025-08-25T20%3A55%3A42Z&sp=r&sv=2024-08-04&sr=b&scid=2658701c-5be2-54b2-bcdb-1275638199d9&skoid=6658dbdd-f305-4d30-8f6b-d62218202cb9&sktid=a48cca56-e6da-484e-a814-9c849652bcb3&skt=2025-08-25T19%3A45%3A43Z&ske=2025-08-26T19%3A45%3A43Z&sks=b&skv=2024-08-04&sig=eI5mpIPeAXNoSjcynE%2BJt8c3CTYQNLptsCvKhRfvgJo%3D)

It;s Combinational digital circuit that performs arithmetic and bitwise operations on integer binary numbers and i adjust it and show numbers by Seven-Segment not on Led only, ,It’s Combinational digital circuit that performs arithmetic and bitwise operations on integer binary numbers and i adjust it and show numbers by Seven-Segment not on Led only, Alu contains 8perationoperation a mix between arithmetic and logical such as Addition, Subtraction, Comparison, AND, OR, XOR, XNOR, NAND. First we designed each operation alone and connected them using multiplexer(MUX).
It’s Combinational digital circuit that performs arithmetic and bitwise operations on integer binary numbers and i adjust it and show numbers by Seven-Segment not on Led only, ,It’s Combinational digital circuit that performs arithmetic and bitwise operations on integer binary numbers and i adjust it and show numbers by Seven-Segment not on Led only, Alu contains 8perationoperation a mix between arithmetic and logical such as:
- Addition
- Subtraction
- Comparison
- AND
- OR
- XOR
- XNOR
- NAND
. First we designed each operation alone and connected them using multiplexer(MUX).


## 🔧 Features

- **4-bit inputs**: A[3:0] and B[3:0]
- **Supported operations** (selectable via 3-bit control):
1. Addition (A + B)  
2. Subtraction (A - B)  
3. Comparison (A > B)  
4. Bitwise AND (A & B)  
5. Bitwise OR (A | B)  
6. Bitwise XOR (A ^ B)  
7. Bitwise XNOR (A ⊙ B)  
8. Bitwise NAND (¬(A & B))

- **Outputs**:
  - 4-bit result
  - Optional: status flags (e.g., Zero, Carry)

- **Display**:
  - 7-segment display to show the output result in decimal
  - leds to show the output reults in binary

## 🧠 Logic Design

The ALU is designed as a purely combinational digital circuit and includes the following components:

- **Basic logic gates**: AND, OR, XOR, XNOR, NAND for bitwise operations
- **Comparator circuit**: To perform binary comparison between A and B
- **4-bit adder/subtractor**: Built from full adders to handle arithmetic operations
- **Multiplexers (MUX)**: Used to select one of the 8 operations based on a 3-bit control signal
- **7-segment display decoder**: Converts binary output to human-readable digits
- **Control logic**: Determines which operation is active based on user input


## 📷 Schematic

 <img src="https://i.postimg.cc/JhZfDhtD/Whats-App-Image-2025-08-25-at-21-50-06-44859d64.jpg" width="105" />  <img src="https://i.postimg.cc/6qFs44VZ/Circuit.jpg)](https://postimg.cc/SYL1wsvQ) " width="420" />  

*4-bit ALU schematic with operation selection and 7-segment output*


## 📌 Notes

- Designed purely with logic gates (no microcontrollers or programming)
- Educational project to demonstrate basic ALU design
- Can be expanded to support more operations or bits

                                     
<div align="right">
<a href="mailto:zezorehan938@gmail.com">𝓩𝓲𝓪𝓭𝓻𝓮𝓱𝓪𝓪𝓷</a>  

</div>


