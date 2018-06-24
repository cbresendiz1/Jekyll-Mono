---
layout: post
title: My experiences in PLDI
author: Charly Resendiz
---

PLDI (Programming Language Design and Implementation), a conference on the field of programming languages and programming systems research, was hosted at Philadelphia, Pennsylvania this year.
PLDI 2018 held 3 phenomenal keynote speakers : Ranjit Jhala, Erik Meijer, Margaret Martonosi. The DeepSpec talks were among my favorite talks, specifically ones with verified C and RISC-V.
This post is meant to capture my experiences from PLDI.

## The Liberty Bell (Interesting?)
-----

Having lived in Pennsylvania for 11 years, in the outskirts of Philadelphia, the thought that the Liberty Bell would be an amazing tourist spot never occured to me. Professors and students alike, throughout the PLDI conference, visited the Liberty Bell, interested in learning about the Founding Fathers. Having taken AP US History in my Junior year of high school, I assumed Philadelphia's history was well-known, but now that is not the case.

## Ranjit Jhala (Keynote)
-----

    Ranjit Jhala, a professor at the University of California, San Diego, delivered a keynote on refinement types, its use in LiquidHaskell, and possible applications in the future.
The keynote made it a point to draw attention on the disconnect between the verification process and software development, explaining that verification and software development
, rarely, influenced the other. Verification often runs after development and code checks, requiring large or subtle changes to satisfy predicates and invariants if the changes fail. Dr. Jhala offered an alternative to developing verified software, "Why not verify while compiling changes, influencing developers software while developing?" At first, I couldn't imagine how that would be possible
with LiquidHaskell, which 2 - 3 years ago did not having many features, but after his demo and explanation I was convinced at the possibilities.

