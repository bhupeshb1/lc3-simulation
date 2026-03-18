# lc3-simulation

Simulated little computer 3 using C It has 16 opcodes, 16 bit (unsigned) memory allocation (65K) & 10 CPU registers. Capable of running 2048 (Linux/Unix only).

Here is the **same README but with tasteful emojis** so it still looks professional on GitHub while being more visually engaging.

---

# 🖥️ LC-3 Virtual Machine (C)

A simple **LC-3 virtual machine implementation written in C** that simulates the execution of LC-3 assembly programs. This project was built to explore how computers execute instructions at a low level and to better understand core computer architecture concepts.

The program emulates the **LC-3 instruction set architecture**, including registers, memory, instruction decoding, and basic device I/O. The LC-3 is a small educational computer architecture commonly used to teach computer organization and assembly programming fundamentals.

---

# 📌 Overview

This virtual machine simulates the behavior of the **Little Computer 3 (LC-3)** architecture.

The LC-3 is a **16-bit educational computer architecture with 8 general-purpose registers and a 65,536-location memory space**.

The VM loads LC-3 object files and executes them using the standard CPU cycle:

1️⃣ **Fetch** instruction from memory
2️⃣ **Decode** opcode and operands
3️⃣ **Execute** instruction and update registers/memory

This project demonstrates how a processor interprets and executes machine instructions.

---

# ✨ Features

* 🧠 Simulates **LC-3 memory (65,536 16-bit locations)**
* 🧾 Implements **LC-3 registers (R0–R7, PC, condition flags)**
* ⚙️ Supports the **fetch–decode–execute instruction cycle**
* 🔢 Implements LC-3 instruction types such as:

  * Arithmetic (`ADD`)
  * Logical (`AND`, `NOT`)
  * Memory operations (`LD`, `ST`, `LDR`, `STR`)
  * Control flow (`BR`, `JMP`)
  * Trap routines for simple I/O
* ⌨️ Supports **memory-mapped keyboard input**
* 🖥️ Console output through LC-3 trap routines

---

# 🏗️ Architecture Components

The VM simulates the core components of the LC-3 processor.

### 📋 Registers

* R0–R7 general purpose registers
* Program Counter (PC)
* Condition Flags (N, Z, P)

### 💾 Memory

* 65,536 memory locations storing **16-bit values**

### 🧩 Instruction Set

Instructions are encoded as **16-bit opcodes** that determine how the CPU processes data and memory.

---

# ▶️ Running the Program

### Compile

```bash
gcc main.c -o lc3
```

### Run with an LC-3 object file

```bash
./lc3 program.obj
```

The VM loads the program into memory and begins executing instructions.

---

# 🎯 Motivation

This project was created to gain hands-on experience with **computer architecture and systems programming**.

Building a virtual machine provides insight into:

* ⚙️ How instructions are decoded and executed
* 🧠 How registers and memory interact
* 🖥️ How low-level programs run on real hardware

Although the LC-3 architecture is simplified, it reflects many of the same principles used in modern processors.

---

# 📚 What I Learned

* Systems programming in **C**
* CPU architecture fundamentals
* Instruction decoding and execution
* Debugging complex stateful systems
* Memory management and **bit manipulation**

---

# 🚀 Future Improvements

* 🔍 Debugging tools for inspecting registers and memory
* 📊 Execution tracing for visualization
* ⚡ Performance optimizations
* 🧩 Additional LC-3 instruction support

---

# 📖 References

* *Introduction to Computing Systems* — Yale N. Patt & Sanjay Patel
* LC-3 Architecture documentation

---

If you want, I can also help you add a **diagram of the LC-3 architecture + fetch-decode-execute cycle**, which makes the repo look **10× more impressive to recruiters.**

