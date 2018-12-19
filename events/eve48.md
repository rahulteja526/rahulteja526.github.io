---
title: Invited Talk by Mr.Pramod Subramanyan on Verifying Security Properties in Modern SoCs Using Instruction-Level Abstractions
---

##### **Invited Talk by Mr.Pramod Subramanyan on Verifying Security Properties in Modern SoCs Using Instruction-Level Abstractions**
**Title:**  Verifying Security Properties in Modern SoCs Using Instruction-Level Abstractions  
**Speaker:** Mr.Pramod Subramanyan  
**Host Faculty:** Dr. Saurabh Joshi  
**Room No:** 519  
**Time:** 11:00  
 
**Abstract:**

Modern Systems-on-Chip (SoC) designs comprise interacting intellectual property (IP) blocks which are often sourced from third-party vendors and contain both hardware accelerators and programmable cores executing firmware. Verifying that SoCs meet their security requirements in this context is especially challenging. These challenges relate to (i) specifying security properties for verification, and (ii) co-verification of these properties across firmware (FW) and hardware (HW).

This talk will describe a methodology for system-level security verification of SoCs. We address the FW/HW co-verification challenge by raising the level of abstraction of the hardware modules to be similar to that of instructions in software/firmware. This abstraction, referred to as an instruction-level abstraction (ILA), plays a role similar to the instruction set architecture (ISA) for general purpose processors and enables high-level analysis of SoC firmware. In particular, the ILA can be used instead of the cycle-accurate and bit-precise register transfer level (RTL) implementation for scalable verification of system-level security properties in SoCs.

Manual construction of the ILA in the context of third-party IPs can be challenging. Hence, we introduce techniques to semi-automatically synthesize the ILA using a template abstraction and directed simulations of the SoC hardware. We describe techniques to ensure that the ILA is a correct abstraction of the underlying hardware implementation. We then show how the ILA can be used for SoC security verification by designing a specification language for security properties and an algorithm based on symbolic execution to verify these properties. We discuss two case studies of applying ILA-based verification to (i) an SoC built out of open source components and (ii) part of a commercial SoC. The methodology discovered several bugs in the RTL implementations, simulators and firmware.

**Speaker's Bio:**

Pramod Subramanyan is a PhD student in the Department of Electrical Engineering at Princeton University where he is advised by Prof. Sharad Malik. His research addresses hardware and firmware security concerns using formal algorithms and analyses.

Prior to joining Princeton, Pramod obtained his M.Sc. (Engg.) degree at the Supercomputer Education and Research Center at the Indian Institute of Science, where his thesis was awarded the Subramaniam Rajalakshmi Medal. He is also a recipient of the Wu Prize for Excellence from the School of Engineering and Applied Sciences at Princeton, a departmental teaching assistant award and the Best Student Paper Award at HOST 2015

**Dates:**  
Wednesday, September 7, 2016 - 11:00