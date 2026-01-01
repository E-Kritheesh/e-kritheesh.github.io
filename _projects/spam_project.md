---
layout: page
title: SPAM
description: Streamlined Prefetcher-Aware Multi-Threaded Covert-Channel
img: assets/img/spam.jpg
importance: 1
category: Research
related_publications: kritheesh2025spam
---

Guide: [Prof. Biswabandan Panda](https://www.cse.iitb.ac.in/~biswa/)

In this project, we proposed a novel **last‑level cache (LLC) covert‑channel attack** that leverages **hardware prefetchers** by carefully tuning memory access patterns to selectively trigger or bypass them. Building on a literature review of Intel’s IP‑stride and stream prefetchers, I extended the state‑of‑the‑art **Streamline** attack to **multi‑core** systems with **distinct** sender and receiver access patterns: senders exploit prefetchers to accelerate encoding, while receivers circumvent them for precise latency measurements.

Key contributions include:

- Accelerating covert communication by selectively triggering or bypassing **hardware prefetchers**, after a literature review of the **Intel IP-stride** and **stream prefetchers**.
- Advanced the bit rate of the state-of-the-art covert-channel **Streamline** by over **70%** in **multi-core** systems for comparable error rates.
- Enhanced **resilience** against defenses by investigating mitigations of flush-based channels.
- Tested attacks rigorously by **injecting noise** using **stress-ng** workloads co-running on other threads.
- Co-authored the paper of the work published at **IEEE Computer Architecture Letters 2025**.

**<u>Link</u>:** [Paper](https://www.cse.iitb.ac.in/~biswa/CAL25.pdf)