# ALU 4bit - 8 Operations

This project implements a **4-bit Arithmetic and Logic Unit (ALU)** capable of performing 8 different operations. The circuit is designed using basic logic gates and multiplexers in a digital logic simulation environment (e.g., Logisim or similar).

## 🔧 Features

- **4-bit inputs**: A[3:0] and B[3:0]
- **Supported operations** (selectable via 3-bit control):
  1. Addition (A + B)
  2. Subtraction (A - B)
  3. Bitwise AND (A & B)
  4. Bitwise OR (A | B)
  5. Bitwise XOR (A ^ B)
  6. Bitwise NOT (on A)
  7. Increment A (A + 1)
  8. Decrement A (A - 1)

- **Outputs**:
  - 4-bit result
  - Optional: status flags (e.g., Zero, Carry)

- **Display**:
  - 7-segment display to show the output result in decimal
  - leds to show the output reults in binary

## 🧠 Logic Design

The design consists of:
- Logic gates (AND, OR, XOR, NOT)
- Multiplexers to select between operations
- 4-bit adder/subtractor built from full adders
- Control lines to choose the operation
- Output display section using 7-segment decoder

## 📷 Schematic

 <img src="https://i.postimg.cc/JhZfDhtD/Whats-App-Image-2025-08-25-at-21-50-06-44859d64.jpg" width="105" />  [![Circuit.jpg](https://i.postimg.cc/6qFs44VZ/Circuit.jpg)](https://postimg.cc/SYL1wsvQ)
*4-bit ALU schematic with operation selection and 7-segment output*


## 📁 Files

- `alu-4bit.circ` or project file (depending on your simulator)
- `README.md` (this file)
- Schematic image

## 📌 Notes

- Designed purely with logic gates (no microcontrollers or programming)
- Educational project to demonstrate basic ALU design
- Can be expanded to support more operations or bits

## 👨‍💻 Author

- [ziadrehaan]
- [[GitHub Profile or Contact Info if you want](https://github.com/ziadrehaan)]

