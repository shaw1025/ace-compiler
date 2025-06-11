---
layout: pubs
title:  "A High-Performance, Conflict-Free Memory-Access Architecture for Modular Polynomial Multiplication"
brief:  "Memory-based NTT"
date:   2023-09-18
author: Bo Zhang
---

### Abstract

In this article, we present the HiCoP architecture, a high-performance, conflict-free memory access, modular polynomial multiplication design that accelerates the number-theoretic transform (NTT), inverse NTT (INTT), and modular polynomial multiplications. To optimize hardware costs, the HiCoP architecture utilizes a high-radix reconfigurable butterfly unit (RBU) that can be dynamically configured to perform NTT, INTT, and point-wise multiplications, alongside an area-efficient Montgomery modular multiplier (MMM) tailored for NTT-friendly modulus. Moreover, by integrating pre-processing, post-processing, and Montgomery domain transformations into NTT and INTT operations, we effectively minimize the cycle count for modular polynomial multiplication. Additionally, we propose a novel conflict-free memory access algorithm that simplifies the control logic and eliminates the need for ping-pong memory in the HiCoP architecture. Experimental results of modular polynomial multiplications demonstrate significant performance gains for the HiCoP architecture implemented on the Xilinx Virtex-7 field-programmable gate array (FPGA) platform, with up to 8.75× , 4.15× , 10.57× , and 8.50× improvements in throughput-to-hardware-cost ratio for LUT count, FF count, BRAM count, and DSP count, respectively.

### MLA Format

Cheng, Zeming, Bo Zhang, and Massoud Pedram. "A high-performance, conflict-free memory-access architecture for modular polynomial multiplication." IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems 43.2 (2023): 492-505.

[[Paper Download]](https://ieeexplore.ieee.org/abstract/document/10254605)

