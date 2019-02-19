---
layout: post
title: "CVC4 at Vienna Summer of Logic"
author: "Clark Barrett"
---

CVC4 won several honors at the “Olympic Games” at the Vienna Summer of Logic.
CVC4 won the most divisions of the SMT-COMP competition (14). Yices won the
second most divisions (10). Unfortunately, both CVC4 and Yices got wrong
answers due to bugs uncovered by the benchmark scrambling, disqualifying them
from receiving an olympic medal.  Medals instead went to veriT and SMTInterpol.

{% include image.html url="/assets/img/vienna-summer-of-logic.jpg"
description="(Left) 'Forall' award for outstanding performance in SMT-COMP.
(Middle) First place trophy for TFA division of CASC. (Right) Kurt Goedel medal
also for winning the TFA division of CASC." %}

Note that Z3 was not an official competitor this year.  If it had been, Z3
would have won 16 divisions, CVC4 would have won 7, and Yices would have won 6.
With the CVC4 bug-fix, the numbers would have been  15 for Z3, 9 for CVC4 (and
still 6 for Yices).  CVC4 performed especially well in quantified divisions and
arithmetic, due to excellent work by Andrew Reynolds[^1] [^2] and Tim
King.[^3] [^4]  With the bug-fix, performance was also quite good in `QF_BV`,
coming in behind Boolector and STP, thanks to recent improvements by Liana
Haderean and others (see [^5]).  Z3 did especially well in divisions containing
non-linear arithmetic (`AUFNIRA`, `NIA`, `NRA`, `QF_NIA`, `QF_NRA`, `QF_UFNIA`,
`QF_UFNRA`, `UFNIA`), where other solvers generally have very limited
capabilities.  Omitting these divisions, the numbers are 9 for Z3, 7 for CVC4
with bug-fix, and 6 for Yices.  Finally, it’s worth noting that if you look at
the “overall” score for all divisions, computed according to the SMT-COMP
rules, Z3 wins with 73.97 and CVC4 (with the bug-fix) is second with 65.56, but
if you omit the non-linear divisions, the score becomes 55.57 for CVC4 and
  54.82 for Z3.  For more details, see the SMT-COMP web site.[^6]

CVC4 also entered CASC, the first-order theorem prover competition, where it
was a surprise winner of the TFA division, and placed 3rd in the FNT division.
Go to the CASC page for more.[^7]

[^1]: [http://cs.nyu.edu/~barrett/pubs/RTG+13-abstract.html](http://cs.nyu.edu/~barrett/pubs/RTG+13-abstract.html)
[^2]: [http://homepage.divms.uiowa.edu/~ajreynol/thesis.pdf](http://homepage.divms.uiowa.edu/~ajreynol/thesis.pdf)
[^3]: [http://cs.nyu.edu/~barrett/pubs/KBD13-abstract.html](http://cs.nyu.edu/~barrett/pubs/KBD13-abstract.html)
[^4]: [http://cs.nyu.edu/~barrett/pubs/KBT14-abstract.html](http://cs.nyu.edu/~barrett/pubs/KBT14-abstract.html)
[^5]: [http://cs.nyu.edu/~barrett/pubs/HBJ+14-abstract.html](http://cs.nyu.edu/~barrett/pubs/HBJ+14-abstract.html)
[^6]: [http://smtcomp.sourceforge.net/2014/results-toc.shtml](http://smtcomp.sourceforge.net/2014/results-toc.shtml)
[^7]: [http://www.cs.miami.edu/~tptp/CASC/J7/WWWFiles/DivisionSummary1.html](http://www.cs.miami.edu/~tptp/CASC/J7/WWWFiles/DivisionSummary1.html)
