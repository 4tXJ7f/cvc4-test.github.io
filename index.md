---
layout: default
---

# About CVC4

CVC4 is an efficient open-source automatic theorem prover for <a
href="http://en.wikipedia.org/wiki/Satisfiability_Modulo_Theories">satisfiability
modulo theories</a> (SMT) problems. It can be used to prove the validity (or,
dually, the satisfiability) of first-order formulas in a large number of
built-in logical theories and their combination.

CVC4 is the fourth in the Cooperating Validity Checker family of tools (CVC,
CVC Lite, <a href="http://cs.nyu.edu/acsys/cvc3/">CVC3</a>) but does not
directly incorporate code from any previous version. A joint project of
Stanford University and U Iowa, CVC4 aims to support the  features of CVC3
and<a href="http://www.smtlib.org/"> SMT-LIBv2</a> while optimizing the design
of the core system architecture and decision procedures to take advantage of
recent engineering and algorithmic advances.

CVC4 is intended to be an open and extensible SMT engine, and it can be used as
a stand-alone tool or as a library, with essentially no limit on its use for
research or commercial purposes (see <a title="Copyright"
href="http://cvc4.cs.stanford.edu/web/copyright/">license</a>). Contributors to
CVC4 are required to sign a Contributor License Agreement (CLA), which can be
found <a title="http://cvc4.cs.nyu.edu/web/cla/"
href="http://cvc4.cs.stanford.edu/web/cla/">here</a>.

## Features

CVC4 works with a version of first-order logic with polymorphic types and has a
wide variety of features including:

- several built-in base theories: rational and integer linear arithmetic,
  arrays, tuples, records, inductive data types, bit-vectors, strings, and
  equality over uninterpreted function symbols
- support for quantifiers
- an interactive text-based interface
- a rich C++ API for embedding in other systems
- model generation abilities

## Documentation

General documentation is available in the <a href="http://cvc4.cs.stanford.edu/wiki">CVC4 wiki</a> which includes the <a href="http://cvc4.cs.stanford.edu/wiki/User_Manual">CVC4 user manual</a> and various <a href="http://cvc4.cs.stanford.edu/wiki/Tutorials">tutorials</a>. For detailed documentation on using CVC4 as a library please see the <a title="CVC4 API documentation" href="http://cvc4.cs.stanford.edu/downloads/builds/documentation/public/latest-unstable">API documentation</a>.

## BibTex Entry

If you are citing CVC4, please use the following BibTex entry:

~~~
@inproceedings{BCD+11,
  url       = "<a href="http://www.cs.stanford.edu/~barrett/pubs/BCD+11.pdf">http://www.cs.stanford.edu/~barrett/pubs/BCD+11.pdf</a>",
  author    = "Clark Barrett and Christopher L. Conway and Morgan Deters and
               Liana Hadarean and Dejan Jovanovi{'{c}} and Tim King and
               Andrew Reynolds and Cesare Tinelli",
  title     = "{CVC4}",
  booktitle = "Proceedings of the 23rd International Conference on Computer Aided Verification (CAV '11)",
  series    = "Lecture Notes in Computer Science",
  volume    = 6806,
  publisher = "Springer",
  editor    = "Ganesh Gopalakrishnan and Shaz Qadeer",
  pages     = "171--177",
  month     = jul,
  year      = 2011,
  note      = "Snowbird, Utah",
  category  = "Conference Publications"
}
~~~

## Source Code

The source code for CVC4 is available on
[GitHub](https://github.com/CVC4/CVC4).

## Copyright

Find copyright and (lack of) warranty information for CVC4
[here](https://github.com/CVC4/CVC4/blob/master/COPYING).

## Technical Support

Please send all bug reports to <a title="mailto:cvc-bugs@cs.nyu.edu" href="mailto:cvc4-bugs@cs.stanford.edu" rel="nofollow">cvc4-bugs@cs.stanford.edu</a>, or use the <a title="CVC4 bug tracking system" href="https://github.com/CVC4/CVC4/issues" rel="nofollow">CVC4 issue tracker</a>. If you have a question, a feature request, or would like to contribute in some way, please contact one of the project leaders. <a title="http://www.cs.nyu.edu/mailman/listinfo/cvc-users" href="http://www.cs.nyu.edu/mailman/listinfo/cvc-users" rel="nofollow">The CVC-USERS list</a> is for users of CVC3 and CVC4. We will make periodic announcements to this list and users are also encouraged to use it for discussion.

## Third-party applications

If you are a CVC4 user with an interesting application, and you would like to
share your experience with other CVC4 users, we encourage you to write a
description in our designated open <a
href="http://cvc4.cs.stanford.edu/wiki/Public:Third_Party_Applications">wiki
page</a>.

## Authors

- Kshitij Bansal, _New York University, Google_
- Haniel Barbosa, _The University of Iowa_
- Clark Barrett, _New York University, Google, Stanford University_
- Francois Bobot, _The University of Iowa, Commissariat a l'Energie Atomique_
- Martin Brain, _University of Oxford_
- Christopher Conway, _New York University, Google_
- Morgan Deters, _New York University_ ([in memoriam]({{ "in-memoriam-morgan-deters.html" | relative_url }}))
- Liana Hadarean, _New York University, Mentor Graphics Corporation_
- Dejan Jovanovic, _New York University, SRI International_
- Guy Katz, _New York University, Stanford University_
- Tim King, _New York University, Universite Joseph Fourier, Google_
- Tianyi Liang, _The University of Iowa_
- Paul Meng, _The University of Iowa_
- Aina Niemetz, _Stanford University_
- Andres Noetzli, _Stanford University_
- Mathias Preiner, _Stanford University_
- Andrew Reynolds, _The University of Iowa, EPFL_
- Cesare Tinelli, _The University of Iowa_
- Yoni Zohar, _Stanford University_

## Acknowledgments

CVC4 is supported in part by the following organizations:
<ul>
 	<li><a title="http://www.wpafb.af.mil/AFRL/afosr/" href="http://www.wpafb.af.mil/AFRL/afosr/" rel="nofollow">The Air Force Office of Scientific Research</a> (award FA9550-09-1-0596)</li>
 	<li><a title="http://www.darpa.mil/" href="http://www.darpa.mil/" rel="nofollow">The Defense Advanced Research Projects Agency</a> (awards FA8750-13-2-0241, FA8750-I5-C-0113)</li>
 	<li>The <a href="https://erc.europa.eu/">European Research Council</a> (grant 306595 <a href="http://stator.imag.fr/">“STATOR”</a>)</li>
 	<li><a href="http://www.geglobalresearch.com/">GE Global Research</a></li>
 	<li><a title="Google" href="http://www.google.com/">Google</a></li>
 	<li><a title="http://www.intel.com/" href="http://www.intel.com/" rel="nofollow">Intel Corporation</a></li>
 	<li><a title="http://www.nsf.gov/" href="http://www.nsf.gov/" rel="nofollow">The National Science Foundation</a> (grants <a href="http://www.fastlane.nsf.gov/servlet/showaward?award=0644299">0644299</a>, <a href="http://www.fastlane.nsf.gov/servlet/showaward?award=0914956">0914956</a>, <a title="1049495" href="http://www.nsf.gov/awardsearch/showAward?AWD_ID=1049495">1049495</a>, <a title="1228768" href="http://www.nsf.gov/awardsearch/showAward?AWD_ID=1228768">1228768</a>, <a title="1320583" href="http://www.nsf.gov/awardsearch/showAward?AWD_ID=1320583">1320583</a>)</li>
 	<li><a title="http://www.src.org/" href="http://www.src.org/" rel="nofollow">The Semiconductor Research Corporation</a> (tasks 1850.001, 1850.002)</li>
</ul>
Any opinions, findings and conclusions or recommendations expressed in this site are those of the authors and do not necessarily reflect the views of the organizations listed above.
