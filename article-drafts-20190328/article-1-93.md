# Rice's Theorem - Or Why There Is No Perfect Anti-Virus

Rice's Theorem states that "any nontrivial property of a program is
**undecidable**".  This means that there is no possible program which
can universally answer simple "Yes/No" questions (in computer science,
we call them "decision problems") about the behaviour of the program
we want to test, unless this question can be answered with "Yes" or
"No" for every possible input of the program.

Answering the question of whether a program contains a virus is such a
decision problem.  And as most viruses are hidden inside other
software and do not always expose their real nature, this decision
problem can't be solved according to Rice's theorem.


## Optional text
Most anti-virus software only looks for viruses that are already known.
This problem of finding already known patterns in other programs is
decidable, as those patterns (so-called "signatures") are always
present in the program, no matter whether the virus is currently doing
something or not.

## Author
slp, 2019-03-27
