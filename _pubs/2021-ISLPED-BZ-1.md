---
layout: pubs
title:  "A High-Performance Low-Power Barrett Modular Multiplier for Cryptosystems"
brief:  "Iterative Barrett Modular Multiplication"
date:   2021-08-04
author: Bo Zhang
---

### Abstract

This paper presents a fast architecture for Barrett modular multiplication. By replacing the integer multiplications in each iteration with carry-save compressions and using Booth coding plus operation rescheduling to increase parallelism, we eliminate costly multiplications while concurrently avoiding large-bitwidth additions. Our detailed error analysis proves that intermediate results are always less than twice the modulus. Experimental results show that the removal of multiplication eliminates the need for any DSPs. Even not accounting for this key benefit, compared to the best of prior art results, the proposed design results in 46.8% latency reduction with a similar area.

### MLA Format

Zhang, Bo, Zeming Cheng, and Massoud Pedram. "A high-performance low-power Barrett modular multiplier for cryptosystems." 2021 IEEE/ACM International Symposium on Low Power Electronics and Design (ISLPED). IEEE, 2021.

[[Paper Download]](https://ieeexplore.ieee.org/document/9502490)

