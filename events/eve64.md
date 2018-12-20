---
title: Invited Talk by Prof. Albert Cohen:"Polyhedral Compilation with PENCIL- A Platform-Neutral Compute Intermediate Language for Accelerator Programming"
---

##### **Invited Talk by Prof. Albert Cohen:"Polyhedral Compilation with PENCIL: A Platform-Neutral Compute Intermediate Language for Accelerator Programming"**
**Title:** Polyhedral Compilation with PENCIL: A Platform-Neutral Compute Intermediate Language for Accelerator Programming  
**Speaker:** Prof. Albert Cohen  
**Host Faculty:** Dr.  Ramakrishna Upadrasta  
**Room No:** LH2 (007)  
**Time:** 09:30  

**Abstract:**

Programming accelerators such as GPUs with low-level APIs and languages such as OpenCL and CUDA is difficult, error-prone, and not performance portable. Automatic parallelization and domain specific languages (DSLs) have been proposed to hide complexity and regain performance portability. We present PENCIL, a rigorously-defined subset of GNU C99, enriched with additional language constructs, that enables compilers to exploit parallelism and produce highly optimized code when targeting accelerators. PENCIL aims to serve both as a portable implementation language for libraries, and as a target language for DSL compilers.

We implemented a PENCIL-to-OpenCL compiler using a state-of-the-art polyhedral techniques. The polyhedral compiler is extended to handle data-dependent control flow, non-affine array accesses, and inter-procedural control flow. To demonstrate the potential and performance portability of the PENCIL-to-OpenCL compiler, we consider a number of image processing kernels, a set of benchmarks from the Rodinia and SHOC suites, and DSL embedding scenarios for linear algebra (BLAS), and signal processing radar applications (SpearDE), and present experimental results for four GPU platforms: AMD Radeon HD 5670 and R9 285, NVIDIA GTX 470, and ARM Mali-T604

**Speaker's Bio:​**

Albert Cohen is a senior research scientist at INRIA and a part-time associate professor at École Polytechnique. He graduated from École Normale Supérieure de Lyon, and received his PhD from the University of Versailles in 1999 (awarded two national prizes). He has been a visiting scholar at the University of Illinois and an invited professor at Philips Research, both for six months.  Albert Cohen works on parallelizing and optimizing compilers, parallel programming, and synchronous programming for embedded systems. He will be or has been the general chair of major conferences, including PLDI, PPoPP, HiPEAC, he is a member of the editorial board of ACM TACO and IJPP, and as the program chair of CC and embedded systems track chair of DAC. He coauthored more than 130 peer-reviewed papers and has been the advisor for 24 PhD theses. Several research projects initiated by Albert Cohen resulted in effective transfer to production compilers (GCC and LLVM). In particular, Albert Cohen pioneered the transfer of polyhedral compilation technology into industrial products, including GCC and later LLVM.

**Dates:**  
Monday, November 23, 2015 - 09:30