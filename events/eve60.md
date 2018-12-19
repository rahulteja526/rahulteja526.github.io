---
title: Invited Talk byPrasanth Chatarasi on Polyhedral Optimizations of Explicitly Parallel Programs
---

##### **Invited Talk byPrasanth Chatarasi on Polyhedral Optimizations of Explicitly Parallel Programs**
**Title:** Polyhedral Optimizations of Explicitly Parallel Programs  
**Speaker:** Prasanth Chatarasi  
**Host Faculty:** Dr.Ramakrishna Upadrasta  
**Room No:** 212  
**Time:** 09:00  

**Abstract:**

This talk address the problem of extending polyhedral frameworks to enable analysis and transformations of programs that contain explicit parallelism and unanalyzable data accesses. As a first step, we focus on OpenMP loop parallelism and task parallelism, including task dependences from OpenMP 4.0. The polyhedral model is a powerful algebraic framework that has enabled significant advances to analysis and transformation of sequential affine (sub)programs, relative to traditional AST-based approaches. However, given the rapid growth of parallel software, there is a need for increased attention to using polyhedral frameworks to optimize explicitly parallel programs.  An interesting side effect of supporting explicitly parallel programs is that doing so can also enable optimization of programs with unanalyzable data accesses within a polyhedral framework. 

Our approach first enables conservative dependence analysis of a given region of code.  Next, we identify happens-before relations from the explicitly parallel constructs, such as tasks and parallel loops, and intersect them with the conservative dependences.  Finally, the resulting set of dependences is passed on to a polyhedral optimizer, such as PLuTo and PolyAST, to enable transformation of explicitly parallel programs with unanalyzable data accesses. We evaluate our approach using eleven OpenMP benchmark programs from the KASTORS and Rodinia benchmark suites.  We show that 1) these benchmarks contain unanalyzable data accesses that prevent polyhedral frameworks from performing exact dependence analysis, 2) explicit parallelism can help mitigate the imprecision, and 3) polyhedral transformations with the resulting dependences can further improve the performance of the manually-parallelized OpenMP benchmarks.  Our experimental results show geometric mean performance improvements of 1.62x and 2.75x on the Intel Westmere and IBM Power8 platforms respectively (relative to the original OpenMP versions).

**Speaker's Bio:**

Prasanth Chatarasi is a 2nd year PhD student in the Department of Computer Science at RICE University, Houston, USA and being advised by Prof. Vivek Sarkar and Dr. Jun Shirako. His research interests are in developing optimizing compilers for explicitly parallel programs. He received B.Tech (Hons) in Computer Science and Engineering from Indian Institute of Technology, Hyderabad. Prior to joining PhD program at RICE, he was with Microsoft, Hyderabad developing Microsoft Azure BizTalk services.

**Dates:**  
Monday, January 11, 2016 - 09:00 to 11:00