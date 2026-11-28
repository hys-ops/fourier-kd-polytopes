# Polytopes and mixed extreme points of finite Fourier Kirkwood–Dirac state spaces

**hys-ops · Paper 1 · Public research manuscript**

[Read the full manuscript (PDF)](files/Fourier_KD_Polytopes.pdf) · [LaTeX and Lean replay (ZIP)](files/Fourier_KD_Paper_1_Manuscript_and_Lean.zip) · [SHA-256 checksums](files/SHA256SUMS)

For a finite abelian group with its position and normalized Fourier bases, the KD-positive state space is a polytope **if and only if** the group is trivial or cyclic of prime-power order. Otherwise its mixed extreme states have the cardinality of the continuum and contain a closed embedded interval. For the two-qubit Fourier pair, the paper constructs an explicit rank-three exposed curve and shows how to transfer it to groups containing the binary plane.

The [Bruneton-led note, 23 November 2026 revision](https://github.com/jpbruneton/open_quantum_problems/blob/main/research/entries/kd-z3x3/manuscript/kd-z3x3.tex) classifies when the pure states suffice. Here the further question is whether finitely many states, **including mixed states**, suffice. The manuscript discusses overlap in the prime-pair and Bell-type construction.

The companion replay uses Lean 4.34.1; see Appendix A for the checked statements and for where the written arguments differ from the formal ones. No independent human review is recorded.

[Research page and proof stages](https://hys-ops.github.io/fourier-kd-polytopes/)

## Research contributions and AI use

hys-ops directed the research into whether reusable tests from earlier work could transfer to a different problem. ChatGPT and Codex contributed to developing the mathematical arguments, drafting the manuscript, and writing the Lean formalization.

## Paper 2: Infinite-rank extreme states

[Read Paper 2 and its six proof pages](https://hys-ops.github.io/fourier-kd-polytopes/paper-2/), including the full manuscript and Lean replay. Paper 2 asks when one extreme state can have infinite rank; it is distinct from the finite-dimensional classification above.

## Paper 3: Central Fourier KD positivity on nonabelian groups

[Compact groups](https://hys-ops.github.io/fourier-kd-polytopes/paper-3/compact/) · [Countable discrete groups](https://hys-ops.github.io/fourier-kd-polytopes/paper-3/discrete/). Separate written classifications for the two stated classes. The [compact verification page](https://hys-ops.github.io/fourier-kd-polytopes/paper-3/compact/#lean-verification) records Lean checks for SU(2) and PSU(2); the full compact classification is not yet formalized. General noncompact nondiscrete groups are outside these notes.
