---
layout: post
title: "2015 Competition Results"
author: "Clark Barrett"
---

CVC4 won several honors at competitions this year.  As with last year, CVC4 won
the most divisions of the main track of the SMT-COMP competition:[^1] of 28
competitive divisions, CVC4 won 12, Yices won 11, Boolector won 3, and CVC3 and
AProVE each won one.  CVC4 was also the overall winner.[^2]  Note that once
again, Z3 was not an official competitor this year, but it was run on the
competition benchmarks for comparison purposes.  If Z3 had been in the
competition, the number of competitive divisions would have increased to 38
with the following breakdown: CVC4 wins 14, Z3 wins 12, Yices wins 8, Boolector
wins 3, CVC3 wins 1.

{% include image.html url="/assets/img/2015-competition.jpg" description="" %}

In addition to SMT COMP 2015, CVC4 entered two other competitions this year:
CASC 25, the competition for automated theorem provers,[^3] and SyGuS Comp
2015, the competition for syntax-guided synthesis solvers.[^4]

In CASC 25, CVC4 entered four divisions.  It won the typed first-order
non-theorems (TFN) division, and came in 2nd in the typed first-order theorems
(TFA) division.  For these divisions, CVC4 used new counterexample-guided
quantifier instantiation methods for handling arithmetic, combined with
E-matching and conflict-based instantiation for handling uninterpreted
functions.  For the latter of these divisions (TFA), it narrowly lost to
VampireZ3, which combines a new approach for Avatar in Vampire with ground
solving in Z3.  It also did fairly well in the first-order theorems division
(FOF), where it placed 5th, only trailing versions of Vampire and E.

In SyGuS Comp 2015, CVC4 entered three tracks, the General track, the
Conditional Linear Arithmetic track, and the Invariant Synthesis track. It won
both the General and Conditional Linear Arithmetic tracks.  It won the latter
track by a significant margin, solving more benchmarks than all other solvers
combined.  It used counterexample-guided quantifier instantiation for both of
these tracks, which is in ongoing development in CVC4.

[^1]: [http://smtcomp.sourceforge.net/2015/results-summary.shtml?v=1446209369](http://smtcomp.sourceforge.net/2015/results-summary.shtml?v=1446209369)
[^2]: [http://smtcomp.sourceforge.net/2015/results-competition-main.shtml?v=1446209369](http://smtcomp.sourceforge.net/2015/results-competition-main.shtml?v=1446209369)
[^3]: [http://www.cs.miami.edu/~tptp/CASC/25/WWWFiles/DivisionSummary1.html](http://www.cs.miami.edu/~tptp/CASC/25/WWWFiles/DivisionSummary1.html)
[^4]: [http://www.sygus.org/SyGuS-COMP2015.html](http://www.sygus.org/SyGuS-COMP2015.html)
