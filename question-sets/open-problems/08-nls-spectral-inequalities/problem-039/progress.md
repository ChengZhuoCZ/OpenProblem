# Progress - problem-039

## Current Status

- Status: scoped
- Summary: Conjecture 5 predicts complete absence of binding for the
  one-dimensional fermionic NLS problem throughout (2\leq p<3). The endpoint
  (p=2) is settled for every (N), and the two-particle case is known in a
  right neighborhood of (p=2); the remaining range is open in the cited
  sources.
- Last updated: 2026-08-06

## What Is Already Organized

- The ambient space is (H^1(\mathbb R;\mathbb C)) with pairwise (L^2)
  orthonormality.
- The energy (\mathcal E_p), density (\rho_{\boldsymbol u}), and infimum
  (J_p(N)) are explicitly defined.
- The conjecture is separated into energy equality and non-attainment.
- The universal upper bound (J_p(N)\leq N J_p(1)) is distinguished from the
  open reverse inequality.
- The original range (2\leq p<3) is recorded, with the settled endpoint
  (p=2) separated from the currently open range (2<p<3).
- The finite-rank Lieb--Thirring route and exponent correspondence are
  recorded as a sufficient stronger approach, not as a proved equivalence.

## Verified Partial Results

- Gontier--Lewin--Nazar formulate the problem as Conjecture 5 and prove
  binding results on the (p<2) side.
- Frank--Gontier--Lewin settle (p=2):
  (J_2(N)=N J_2(1)) for every (N), with no minimizer for (N\geq2).
- Chen--Guo--Luo--Wei prove that there exists (\delta>0) such that
  (J_p(2)) has no minimizer for (2\leq p\leq2+\delta). Together with the
  concentration-compactness criterion, this yields
  (J_p(2)=2J_p(1)) in that interval.
- The same 2026 work gives a refined two-bump description as (p\uparrow2),
  with separation on the scale ((2-p)^{-1/2}).
- Guo--Luo--Wei classify the finite-energy solutions of the cubic
  (N)-component system at (p=2), strengthening the structural picture at
  the settled endpoint.

## Open Clarifications

- Determine the largest interval in (p>2) for which the two-particle
  nonexistence method can be made uniform.
- Decide whether the equality (J_p(N)=N J_p(1)) can be proved inductively in
  (N) without first classifying all possible multi-particle clusters.
- Identify the precise finite-rank Lieb--Thirring statement minimally needed
  for the NLS lower bound.
- Separate nonexistence of a minimizer from the stronger assertion of complete
  splitting into one-particle clusters for (N\geq3).
- Track revisions or publication status of the 2026 preprints before upgrading
  any result from preprint status.

## Next Actions

- Build a lemma-level implication map from finite-rank Lieb--Thirring bounds to
  (J_p(N)\geq N J_p(1)).
- Analyze the (N=2) problem away from (p=2), where the small-parameter
  Pohozaev expansion is no longer available.
- Formulate a profile-decomposition statement that distinguishes complete
  one-particle splitting from splitting into larger bound clusters.
- Record exact theorem and proposition locators for every cited partial result.
- Check future arXiv revisions for progress on the remaining range
  (2<p<3).

## Work Log

### 2026-08-06

- Added the problem from Gontier--Lewin--Nazar, Conjecture 5.
- Reconstructed the variational formulation with explicit (p)-dependence.
- Separated the source conjecture, settled endpoint, current open core, binding
  interpretation, and Lieb--Thirring route.
- Verified the principal source and the cited 2026 partial results against
  their arXiv records.
