---
layout: page
title: Bitcoin Proofs
description: Zero-knowledge proofs using Nova in Rust and bellpepper
img: assets/img/btc_proof.jpg
importance: 3
category: Research
giscus_comments: false
---

**BTech Project 2 - EE 492**

Guide: [Prof. Saravanan Vijayakumaran](https://www.ee.iitb.ac.in/~sarva/)

**Validity Proofs for Bitcoin Header Chain Using Nova**  

Developed a **zero-knowledge proof** system to validate Bitcoin’s header chain without block-by-block verification. Proved **Bitcoin header consensus rules** (proof-of-work, target adjustment, timestamps, and previous hash) using R1CS constraints and recursive SNARKs via **Nova, Rust, and bellpepper libraries**. Tested with **8000+ blocks** to show efficient proof generation and verification, enabling compact chain state validation for **light clients** and other use-cases such as **BTC relay**, and **cross-chain** applications.

**<u>Links</u>:** 
1. [Presentation](https://drive.google.com/file/d/1u13sc1aenG7MPC6JgFLG6CInKgO7hoU4/view?usp=sharing)
2. [Report](https://drive.google.com/file/d/1vgkEczMjE568-jSAHkdDBANVA8VVbeRm/view?usp=sharing)
3. [Code](https://github.com/E-Kritheesh/btc-validity-proof/)