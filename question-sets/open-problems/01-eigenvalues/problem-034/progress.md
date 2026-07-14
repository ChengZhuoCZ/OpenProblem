# Progress - problem-034

## Current Status

- Status: scoped
- Summary: The problem asks for the best quantitative Faber-Krahn constant in the class of planar open convex sets of area \(\pi\), with a fallback target of a fully explicit computable lower bound.
- Last updated: 2026-07-14

## What Is Already Organized

- The admissible class is fixed as bounded open convex sets \(\Omega\subset\mathbb R^2\) with \(|\Omega|=\pi\).
- The reference optimizer is the unit disk \(B\), with \(\lambda_1(B)=j_{0,1}^2\).
- The normalized Fraenkel asymmetry is recorded as
  \[
  \mathcal A(\Omega)=\inf_{x\in\mathbb R^2}
  \frac{|\Omega\triangle(x+B)|}{\pi}.
  \]
- The main variational quotient is
  \[
  \mathcal Q(\Omega)
  =
  \frac{\lambda_1(\Omega)-j_{0,1}^2}
  {\mathcal A(\Omega)^2}.
  \]
- The two active goals are:
  1. determine the exact value of \(C_{2,\mathrm{conv}}^{\mathrm{opt}}\);
  2. if exact sharpness is out of reach, prove an explicit computable lower bound.

## Open Clarifications

- Determine whether the infimum is attained by a non-disk convex set or only by sequences approaching the disk.
- Decide which class of near-disk perturbations should be analyzed first for upper bounds.
- Identify the best available explicit quantitative Faber-Krahn constants in dimension two.
- Check whether convexity allows substantially sharper constants than the general measurable-set inequality.
- Decide whether the first rigorous output should be a numerical certified lower bound or an analytic closed-form estimate.

## Next Actions

- Collect known quantitative Faber-Krahn stability results and record which constants are explicit.
- Compute \(\mathcal Q(\Omega)\) for simple convex competitors to produce benchmark upper bounds.
- Set up the shape-derivative expansion of \(\lambda_1\) and \(\mathcal A\) near the disk.
- Build a table separating local near-disk estimates from global estimates away from the disk.
- If using a numerical lower bound, specify the interval-arithmetic certification pipeline.

## Work Log

### 2026-07-14

- Added the problem as a new eigenvalue/spectral-geometry entry.
- Split the target into exact sharp constant and explicit computable lower-bound versions.
- Recorded the equivalent optimization formulation via \(\mathcal Q(\Omega)\).
