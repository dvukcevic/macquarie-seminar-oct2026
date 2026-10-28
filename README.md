# Verifying elections with anytime-valid methods

A statistics seminar given by [Damjan Vukcevic][damjan] at
Macquarie University on 29 Oct 2026.

[damjan]: http://damjan.vukcevic.net/


## Abstract

There is growing interest in “anytime-valid” statistical methods, which allow
researchers to continuously monitor data and stop sampling once sufficient
evidence has been collected.  Unlike traditional fixed-sample analyses, these
sequential methods permit “peeking” and are immune to “p-hacking”.  While these
methods originated in the 1940s, they have historically been underutilised
outside of specific fields like clinical trials.  Today, the area is
experiencing a resurgence as analysts look for methods that offer a “safe” way
to conduct multiple looks at data and flexibility in deciding when to stop.

In this talk, I will introduce key foundational concepts for those new to
sequential analysis.  This will include test supermartingales and Ville’s
inequality, which enable rigorous finite-sample inference without relying on
asymptotic theory.

I will then demonstrate how these tools can be applied to verify the outcomes
of preferential elections via efficient post-election audits. This application
poses a challenging high-dimensional inference problem, which we address by
fusing sequential analysis with combinatorial optimisation to minimise required
sample sizes while guaranteeing finite-sample error control.


## Licence

[![Creative Commons License][cc-img]][cc]  
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0
International License][cc].

[cc]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-img]: https://i.creativecommons.org/l/by-sa/4.0/88x31.png
