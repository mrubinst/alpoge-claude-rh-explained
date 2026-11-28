# Expository papers on the Lean proofs of the Riemann hypothesis

Two papers by Michael O. Rubinstein, written with Claude, Codex and Gemini, as aids to studying the proofs in
the language of classical analytic number theory. Both are works in progress.

## An outline of the shortened proof of the Riemann Hypothesis

**Version 1.5, 27 November 2026**

- [rh-outline.pdf](rh-outline.pdf) (45 pages)
- [rh-outline.tex](rh-outline.tex) (LaTeX source; a single self-contained file, compile with pdflatex three times)

A study guide, in fifteen steps, to the shortened Lean proof of the Riemann hypothesis and of the generalized
Riemann hypothesis for Dirichlet L-functions released on 25 November 2026 by Luke Sernau, colleagues at
Anthropic and Claude ([lsernau/grh-lean](https://github.com/lsernau/grh-lean)). Steps 1-4 reduce the Riemann
hypothesis to a one-sided bound for a sum over the primes inert in an imaginary quadratic field; the first three
are proved in the paper and the fourth, a zero-density estimate, is outlined. Steps 5-10 explain the mechanism
and deduce that bound from three theorems, A, B and C, of the Lean development; the deduction is proved in the
paper. The three theorems themselves are stated and their proofs are outlined (Steps 11-14), but they are not
proved there: they rest on the formal proof. An appendix works three small numerical examples.

## The Alpöge–Claude proof of the Riemann hypothesis explained for the Riemann zeta function

Claude Fable 5.2, Codex Astra 6.2, and Gemini Carbon, at the behest of Michael O. Rubinstein.

**Version 2, working draft, 22 November 2026**

- [zeta-paper_v2.pdf](zeta-paper_v2.pdf) (265 pages)
- [zeta-paper_v2.tex](zeta-paper_v2.tex) (LaTeX source; a single self-contained file, compile with pdflatex three times)

First version, 21 November 2026: [zeta-paper.pdf](zeta-paper.pdf) (164 pages), [zeta-paper.tex](zeta-paper.tex).

A working guide to Levent Alpöge's Lean-verified proof of the Riemann hypothesis, specialised to the Riemann
zeta function, written as an aid to studying the proof in the language of classical analytic number theory.
It deduces the Riemann hypothesis from the main inequality (M), an upper bound for a weighted sum over prime
powers, and two estimates for Dirichlet characters, which it proves, for suitably chosen auxiliary primes, from
theorems in the literature. (M) itself is not proved there: the paper reduces it, and with it the Riemann
hypothesis, to thirteen numbered hypotheses stated in classical terms, none of which is proved outright, and
states which inputs it takes from the Lean development. Section I.12 lists what remains to be
written up. Version 2 adds the objects of the construction, the reduction of (M) to numbered hypotheses, the
lemniscate worked in full, and a census of the published results the Lean development uses.
This is a work in progress.

Part I (pages 3–28 of version 2) gives the whole strategy with worked examples.

Project page: https://www.math.uwaterloo.ca/~mrubinst/alpoge_claude_grh/
Independent check of the Lean proof: https://mrubinst.github.io/grh-lean-verification/
