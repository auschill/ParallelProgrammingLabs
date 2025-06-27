---
layout: default
title: Install Vitis
parent: Preparation
nav_order: 2.01
---

# Start setting up your board

# FPGA Board and Vitis Installation Guide.
In this course, we will be using the AMD AUP ZU3 board, provided through the AMD University Program. The course covers topics such as FPGA architecture, Verilog testbenches and verification, finite state machines (FSMs), and digital computer design.

We will use the AMD Vivado and Vitis software suite throughout this course:

Vivado is a design tool that synthesizes Verilog code into gate-level implementations for FPGAs. It enables you to perform RTL synthesis, implement your design onto the FPGA, and run simulations to verify functional behavior.

Vitis is AMD’s High-Level Synthesis (HLS) tool, which compiles C or C++ code into synthesizable RTL, allowing high-level algorithmic designs to be implemented on the FPGA.


# What is Verilog?
Verilog is a hardware description language, it is not a programming language. Verilog is used to describe hardware functionality in order to design 
a circuit for implementation. 

# What is RTL?

RTL stands for Register Transfer level and refers to the level above transistor level. This includes Registers,nets, wires, memory, I/o ports. Verilog is written
at the "Register Transfer Level".

# Acquire AMD AUP ZU3 Board.
You’re not restricted to the following vendor, but it’s an example of the product you need. [Example Purchase Link](https://www.realdigital.org/hardware/aup-zu3 )




# Register with AMD
It is necessary to create an AMD account to receive the Download.
Create your AMD account here: [AMD Account Registration](https://www.amd.com/en/registration/create-account.html)

# Get Vitis Software
Download Vitis™ Unified Software Platform 2023.2 from Vitis Download Page. Ensure your computer is compatible. IMPORTANT -> If you wish to download/run Vitis/Vivado to your laptop/local PC.
A couple notes
1. It is difficult for Macbooks with ARM arch (M1, etc). Because you will need to use a virtual machine for windows/linux to run the program. Because Vivado needs x86_64 architecture.
2. Vitis/Vivado as a package takes up around 90-100 GB of Hard drive space. So ensure you have plenty of Storage.
3. Vitis/Vivado will only really run comfortably with 20+ GB of RAM. You can try to do 16 GB but it will likely be slow.

# A note for Clemson University Students 
Vitis/Vivado is already installed on computers in Cadence Lab, Riggs B22. So, use that!

Proceed with Vitis Installation.
