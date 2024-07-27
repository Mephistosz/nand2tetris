# The Elements of Computing Systems: Building a Modern Computer from First Principles

## Description
This project documents my journey through the Nand2Tetris course, exploring the elements of computing systems from the ground up.

## Resources

**Books and Websites:**
- Book: [The Elements of Computing Systems, Second Edition](https://mitpress.mit.edu/books/elements-computing-systems-second-edition)
- Website: [Nand2Tetris](https://www.nand2tetris.org/)

**Digital HDL Tools:**
- [Digital by hneemann](https://github.com/hneemann/Digital)
- [Digital Logic Sim by SebLague](https://github.com/SebLague/Digital-Logic-Sim)
- [Nand2Tetris VS Code Plugin](https://marketplace.visualstudio.com/items?itemName=Throvn.nand2tetris)

## Setup Instructions

**Sections 1, 2, & 3:**
- **Running the Hardware Simulator:**
  ```sh
  sh tools/HardwareSimulator.sh
  ```
- **Running the Digital HDL Project:**
  - Clone the repo and build the jar:
    ```sh
    git clone https://github.com/hneemann/Digital
    cd Digital
    mvn package
    java -jar target/Digital.jar
    ```

**Section 4:**
- **Running the CPU Emulator:**
  ```sh
  sh tools/CPUEmulator.sh
  ```

**Section 6:**
- **Running the Assembler:**
  ```sh
  sh tools/Assembler.sh
  ```
- **Running the CPU Emulator:**
  ```sh
  sh tools/CPUEmulator.sh
  ```

## Contents and Progress

### Hardware
- [ ] Boolean Logic
- [ ] Boolean Arithmetic
- [ ] Memory
- [ ] Machine Language
- [ ] Computer Architecture
- [ ] Assembler

### Software
- [ ] Virtual Machine I - Processing
- [ ] Virtual Machine II - Control
- [ ] High-Level Language
- [ ] Compiler I - Syntax Analysis
- [ ] Compiler II - Code Generation
- [ ] Operating System

## Additional Resources
- [Coursera: Build a Modern Computer from First Principles: From Nand to Tetris (Project-Centered Course)](https://www.coursera.org/learn/build-a-computer)
- [Coursera: Build a Modern Computer from First Principles: Nand to Tetris Part II (Project-Centered Course)](https://www.coursera.org/learn/nand2tetris2)

## Credits
This project uses data and resources from [timmywheels' elements-of-computing-systems repository](https://github.com/timmywheels/elements-of-computing-systems).

## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.
