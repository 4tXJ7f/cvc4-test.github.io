---
layout: default
---

# History of CVC

The Cooperating Validity Checker series has a long history. The Stanford
Validity Checker (SVC) came first in 1996, incorporating theories and its own
SAT solver. Its successor, the Cooperating Validity Checker (CVC), had a more
optimized internal design, produced proofs, used the Chaff SAT solver, and
featured a number of usability enhancements. Its name comes from the
cooperative nature of decision procedures in Nelson-Oppen theory combination,
which share amongst each other equalities between shared terms. CVC Lite, first
made available in 2003, was a rewrite of CVC that attempted to make CVC more
flexible (hence the "lite") while extending the feature set: CVC Lite supported
quantifiers where its predecessors did not. CVC3 was a major overhaul of
portions of CVC Lite: it added better decision procedure implementations, added
support for using MiniSat in the core, and had generally better performance.

CVC4 is the new version, the fifth generation of this validity checker line
that is now celebrating sixteen years of heritage. It represents a complete
re-evaluation of the core architecture to be both performant and to serve as a
cutting-edge research vehicle for the next several years. Rather than taking
CVC3 and redesigning problem parts, we've taken a clean-room approach, starting
from scratch. Before using any designs from CVC3, we have thoroughly
scrutinized, vetted, and updated them. Many parts of CVC4 bear only a
superficial resemblance, if any, to their correspondent in CVC3.

However, CVC4 is fundamentally similar to CVC3 and many other modern SMT
solvers: it is a DPLL(T) solver, with a SAT solver at its core and a delegation
path to different decision procedure implementations, each in charge of solving
formulas in some background theory.

The re-evaluation and ground-up rewrite was necessitated, we felt, by the
performance characteristics of CVC3. CVC3 has many useful features, but some
core aspects of the design led to high memory use, and the use of heavyweight
computation (where more nimble engineering approaches could suffice) makes CVC3
a much slower prover than other tools. As these designs are central to CVC3, a
new version was preferable to a selective re-engineering, which would have
ballooned in short order.
