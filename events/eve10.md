---
title: Invited Talk by Dr. Suryajith Chillara on Small-depth Multilinear Formula Lower Bounds for Iterated Matrix
---
<br>
Back to [Events Home Page](/cseevents.html)  
<br>
##### **Invited Talk by Dr. Suryajith Chillara on Small-depth Multilinear Formula Lower Bounds for Iterated Matrix Multiplication, with Applications**
**Title:** Small-depth Multilinear Formula Lower Bounds for Iterated Matrix Multiplication, with Applications  
**Speaker:** Dr. Suryajith Chillara from IITB.
**Host Faculty:**  Dr. Karteek Sreenivasaiah
**Room No:** A-317
**Time:** 14:00 PM - 15:00 PM
**Abstract:**  
The complexity of Iterated Matrix Multiplication is a central theme in Computational Complexity theory, as the problem is closely related to the problem of separating various complexity classes within P. In this paper, we study the algebraic formula complexity of multiplying d many 2 x 2 matrices, denoted IMM_d, and show that the well-known divide-and-conquer algorithm cannot be significantly improved at any depth, as long as the formulas are multilinear (that is, every node in the formula computes a multilinear polynomial). 

Formally, for each depth Delta <= log d, we show that any product-depth Delta multilinear formula for IMM_d must have size exp(Omega(Delta d^{1/Delta})). It also follows from this that any multilinear circuit of product-depth Delta for the same polynomial of the above form must have a size of exp(Omega(d^{1/Delta})). In particular, any polynomial-sized multilinear formula for IMM_d must have depth Omega(log d), and any polynomial-sized multilinear circuit for IMM_d must have depth Omega(log d/log log d). Both these bounds are tight up to constant factors. Our lower bound has the following consequences for multilinear formula complexity. 

--> Depth-reduction: Depth reduction is an an analogue of parallelization, for arithmetic circuits. A well-known result of Brent (JACM 1974) implies that any formula of size s can be converted to one of size s^{O(1)} and depth O(log s); further, this reduction continues to hold for multilinear formulas. On the other hand, our lower bound implies that any depth-reduction in the multilinear setting cannot reduce the depth to o(log s) without a superpolynomial blow-up in size. 

--> Separations from general formulas: Shpilka and Yehudayoff (FnTTCS 2010) asked whether general formulas can be more efficient than multilinear formulas for computing multilinear polynomials. Our result, along with a non-trivial upper bound for IMM_d implied by the results of Gupta, Kamath, Kayal and Saptharishi (SICOMP 2016), shows that for any size s and product-depth Delta = o(log s), general formulas of size s and product-depth Delta cannot be converted to multilinear formulas of size s^{omega(1)} and product-depth Delta, when the underlying field has characteristic zero.

(joint work with Nutan Limaye and Srikanth Srinivasan)

**Note:** Talk will not assume any prior background in circuit complexity and will be self contained.
 
**Speaker Bio:**  
Suryajith works broadly in the area of theoretical computer science and in particular, computational complexity theory. He is currently a post doctoral fellow at the department of CSE, IIT Bombay. He obtained his MSc and PhD degrees from Chennai Mathematical Institute under the supervision of Partha Mukhopadhyay.  He got his undergraduate degree from IIT Kanpur.
**Dates:**  
Thursday, April 12, 2018 - 14:00 to 15:00