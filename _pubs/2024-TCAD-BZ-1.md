---
layout: pubs
title:  "Area-Efficient Barrett Modular Multiplication With Optimized Karatsuba Algorithm"
brief:  "Pipelined Barrett Modular Multiplication"
date:   2024-06-24
author: Bo Zhang
---

### Abstract

This article presents an area-efficient Barrett modular multiplication (BMM) algorithm, facilitating the development of cryptosystems like fully homomorphic encryption. Instead of implementing three normal multiplications required by classic BMM, our proposed BMM introduces optimizations for multiplication AB, truncated multiplication AB/2^f, and modular multiplication (MM) AB mod 2^f. Taking the 4-term Karatsuba algorithm as an example, an N-bit multiplication AB can be decomposed into 9 (N/4)-bit multiplications. Our optimized approaches for truncated multiplication and MM require an area equivalent to only 6.5 (N/4) -bit multiplications when f≈N . Furthermore, our optimized Karatsuba multiplications introduce efficient (E, I) matrix pairs, circumventing area overhead from complex I matrices and sign extension in multiplication. We also employ encode algorithm to eliminate many additions needed in BMM and inside multiplications, significantly shortening critical path. Experimental results demonstrate the advantages of our proposed BMM in terms of throughput and area efficiency.

### MLA Format

Zhang, Bo, and Shoumeng Yan. "Area-efficient Barrett modular multiplication with optimized Karatsuba algorithm." IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (2024).

[[Paper Download]](https://ieeexplore.ieee.org/document/10557644)

