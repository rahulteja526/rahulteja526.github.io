---
title: Polly as an Analysis Pass in LLVM
---
<br>
Back to [CSE Home Page](cse.html)  
<br>

##### **Polly as an Analysis Pass in LLVM**

**Abstract**

The Polyhedral framework provides an exact dependence analysis, which is more powerful than conventional dependence testing algorithms [5, 6]. Currently, LLVM mainline lacks a powerful dependence analysis framework, and at the same time, Polly’s (a high-level data locality optimizer based on polyhedral framework) dependence analysis is suitable for many transformation passes in LLVM like Loop Vectorization, Loop Versioning, Modulo Scheduling, Loop Nest Optimizations, etc. I propose to provide an API for Polly such that its precise dependence analysis can be used as an Analysis pass within LLVM's transformation passes.

The announcement can be found in the below link  
[https://summerofcode.withgoogle.com/organizations/5450930363301888/#5943070403067904](https://summerofcode.withgoogle.com/organizations/5450930363301888/#5943070403067904)