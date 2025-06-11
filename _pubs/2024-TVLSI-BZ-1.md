---
layout: pubs
title:  "Design of a High-Performance Iterative Barrett Modular Multiplier for Crypto Systems"
brief:  "Iterative Barrett Modular Multiplication"
date:   2024-02-29
author: Bo Zhang
---

### Abstract

Modular multiplication (MM) is a fundamental operation in many cryptographic and arithmetic applications. In this article, we present an improved Barrett modular multiplication (BMM) algorithm and its hardware-efficient implementation. The proposed algorithm leverages parallel computation of quotient and intermediate results, enhancing overall efficiency. To further optimize the algorithm, two optimizations are introduced, replacing expensive multiplications and additions with more efficient compression and encoding operations at each iteration. We first introduce a novel data model that enables the use of a 2-bit adder to handle potential overflow in signed addition. Moreover, by employing a 3-bit addition on intermediate results, we eliminate the need for complete round operations while ensuring the desired result range. The experimental results demonstrate significant improvements in terms of area and computation time compared to existing classic BMM and Montgomery modular multiplication (MMM) designs. Our improved BMM outperforms these designs, particularly in high-radix scenarios. This work provides a valuable contribution to the field of MM, offering a hardware-efficient solution for achieving improved performance in cryptographic and arithmetic systems.

### MLA Format

Zhang, Bo, Zeming Cheng, and Massoud Pedram. "Design of a high-performance iterative Barrett modular multiplier for crypto systems." IEEE Transactions on Very Large Scale Integration (VLSI) Systems (2024).

[[Paper Download]](https://ieeexplore.ieee.org/document/10456535)

