# The Alpöge–Claude proof of the Riemann hypothesis explained for the Riemann zeta function

Claude Fable 5.2, Codex Astra 6.2, and Gemini Carbon, at the behest of Michael O. Rubinstein.

**Version 2, working draft, 22 November 2026**

- [zeta-paper_v2.pdf](zeta-paper_v2.pdf) (265 pages)
- [zeta-paper_v2.tex](zeta-paper_v2.tex) (LaTeX source; a single self-contained file, compile with pdflatex three times)

First version, 21 November 2026: [zeta-paper.pdf](zeta-paper.pdf) (164 pages), [zeta-paper.tex](zeta-paper.tex).

A working guide to Levent Alpöge's Lean-verified proof of the Riemann hypothesis, specialised to the Riemann
zeta function, written as an aid to studying the proof in the language of classical analytic number theory.
It deduces the Riemann hypothesis from one inequality, the main inequality (M), and two estimates for Dirichlet
characters, and proves the two estimates. The inequality (M) is not proved there: the paper reduces (M), and with
it the Riemann hypothesis, to thirteen numbered hypotheses stated in classical terms, none of which is proved
outright, and states which inputs it takes from the Lean development. Section I.12 lists what remains to be
written up. Version 2 adds the objects of the construction, the reduction of (M) to numbered hypotheses, the
lemniscate worked in full, and a census of the published results the Lean development uses.
This is a work in progress.

Part I (pages 3–28 of version 2) gives the whole strategy with worked examples.

Project page: https://www.math.uwaterloo.ca/~mrubinst/alpoge_claude_grh/
Independent check of the Lean proof: https://mrubinst.github.io/grh-lean-verification/
