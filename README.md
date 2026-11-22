# The Alpöge–Claude proof of the Riemann hypothesis explained for the Riemann zeta function

Claude Fable 5.2, Codex Astra 6.2, and Gemini Carbon, at the behest of Michael O. Rubinstein.
Working draft, 21 November 2026.

- [zeta-paper.pdf](zeta-paper.pdf) (164 pages)
- [zeta-paper.tex](zeta-paper.tex) (LaTeX source; a single self-contained file, compile with pdflatex three times)

A working guide to Levent Alpöge's Lean-verified proof of the Riemann hypothesis, specialised to the Riemann
zeta function, written as an aid to studying the proof in the language of classical analytic number theory.
It deduces the Riemann hypothesis from one inequality between weighted sums over primes, the main inequality (M),
and two estimates for Dirichlet characters, and proves the two estimates. The inequality (M) is not proved there:
its proof is taken from the Lean development, and the paper states which inputs it takes from it.
This is a work in progress.

Part I (pages 3–23) gives the whole strategy with worked examples.

Project page: https://www.math.uwaterloo.ca/~mrubinst/alpoge_claude_grh/
Independent check of the Lean proof: https://mrubinst.github.io/grh-lean-verification/
