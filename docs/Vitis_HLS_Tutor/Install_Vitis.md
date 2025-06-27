---
layout: default
title: Install Vitis
parent: Preparation
nav_order: 2.01
---

# Start setting up your board

# FPGA Board and Vitis Installation Guide.
In this course, we will be using the AMD AUP ZU3 from AMD university program. This course goes through topics such as: FPGA architecture, verilog
testbenches and verification, Finite State Machines, and Digital computer design. The software suite we will be using for this coures will be the
AMD Vits/Vivado suite. Vivado is a program that takes verilog code and synthesizes it into RTL code that can be implemented and programmed to the FPGA Board. Vivado also allows 
simulations of the verilog code to see how it performs. Vitis is a High Level Synthesis (HLS) tool from AMD that synthesis C++ code into RTL code.


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
1. It is difficult for Macbooks with ARM arch (m1, etc). Because you will need to use a virtual machine for windows/linux to run the program
2. Vitis/Vivado as a package takes up around 90-100 GB of Hard drive space. So ensure you have plenty of Storage.
3. Vitis/Vivado will only really run comfortably with 20+ GB of RAM. You can try to do 16 GB but it will likely be slow.

# A note for Clemson University Students 
Vitis/Vivado is already installed on computers in Cadence Lab, Riggs B22. So, use that!

Proceed with Vitis Installation.
