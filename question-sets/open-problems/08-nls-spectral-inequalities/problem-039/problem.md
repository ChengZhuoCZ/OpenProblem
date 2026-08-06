---
id: problem-039
title: "Absence of binding for one-dimensional fermionic nonlinear Schrödinger systems"
primary_category: "非线性 Schrödinger 方程与谱不等式"
secondary_categories:
  - "变分法"
  - "Lieb-Thirring inequalities"
  - "多体量子系统"
status: "scoped"
created: "2026-08-06"
language: "mixed zh/en"
source:
  title: "The nonlinear Schrödinger equation for orthonormal functions: I. Existence of ground states"
  url: "https://arxiv.org/abs/2002.04963"
  source_problem_number: "Conjecture 5"
  authors: "David Gontier, Mathieu Lewin, and Faizan Q. Nazar"
keywords:
  - fermionic nonlinear Schrödinger equation
  - orthonormal functions
  - absence of binding
  - concentration compactness
  - Lieb-Thirring inequality
  - ground states
---

# Problem 039 - Absence of Binding in One-Dimensional Fermionic NLS

## 1. Variational Setting

Let (N\geq 1) be an integer and let (1<p<3). For an orthonormal family

\[
u_1,\ldots,u_N\in H^1(\mathbb R;\mathbb C),
\qquad
\langle u_j,u_k\rangle_{L^2(\mathbb R)}=\delta_{jk},
\]

define the total density

\[
\rho_{\boldsymbol u}(x)=\sum_{j=1}^N |u_j(x)|^2
\]

and the focusing energy

\[
\mathcal E_p(u_1,\ldots,u_N)
=
\sum_{j=1}^N\int_{\mathbb R}|u_j'(x)|^2\,dx
-\frac1p\int_{\mathbb R}\rho_{\boldsymbol u}(x)^p\,dx.
\]

Set

\[
J_p(N)
=
\inf\left\{
\mathcal E_p(u_1,\ldots,u_N):
u_j\in H^1(\mathbb R;\mathbb C),\
\langle u_j,u_k\rangle_{L^2}=\delta_{jk}
\right\}.
\]

For (N=1), this is the usual mass-one focusing NLS problem, so
(J_p(1)=I_p(1)).

## 2. Source Conjecture

Gontier--Lewin--Nazar's Conjecture 5 states that for every

\[
2\leq p<3,
\qquad
N\geq 2,
\]

one has

\[
\boxed{J_p(N)=N J_p(1),}
\]

and the infimum (J_p(N)) is not attained.

Equivalently, the energetically optimal asymptotic configuration consists of
(N) mutually separating one-particle solitons rather than a finite-size
multi-particle cluster.

The endpoint (p=2) is now known. Thus the unresolved core of the conjecture
is the following statement.

> For every (2<p<3) and every integer (N\geq2), prove that
> (J_p(N)=N J_p(1)) and that (J_p(N)) has no minimizer.

## 3. Binding Interpretation

Separating a (K)-particle configuration from an ((N-K))-particle
configuration gives the universal subadditivity inequality

\[
J_p(N)\leq J_p(K)+J_p(N-K),
\qquad 1\leq K\leq N-1.
\]

If every nontrivial splitting is strict,

\[
J_p(N)<J_p(K)+J_p(N-K),
\qquad K=1,\ldots,N-1,
\]

then concentration compactness yields a minimizer and compactness of
minimizing sequences modulo translations. Conjecture 5 predicts the opposite
extreme: equality after complete splitting into (N) one-particle clusters.

The easy direction is

\[
J_p(N)\leq N J_p(1),
\]

obtained by translating (N) copies of a one-particle minimizer far apart and
then applying a small orthonormalization. The main open estimate is

\[
\boxed{J_p(N)\geq N J_p(1).}
\]

After this lower bound, one must still analyze the equality case to prove
non-attainment.

## 4. Known Partial Results

1. For (p=2) and every (N\geq1),
   \[
   J_2(N)=N J_2(1),
   \]
   and no minimizer exists when (N\geq2).
2. There is a sufficiently small (\delta>0) such that the two-particle
   problem has no minimizer for
   \[
   2\leq p\leq2+\delta.
   \]
   Combining this with subadditivity and the strict-binding compactness
   criterion gives (J_p(2)=2J_p(1)) on the same interval.
3. For (1<p<2), binding is known in substantial regimes. In particular,
   (J_p(2)) has a minimizer throughout this interval, illustrating the
   phase transition at (p=2).

The cited results do not cover (N=2) away from the known right neighborhood
of (p=2), nor the general case (N\geq3) for (2<p<3).

## 5. Lieb--Thirring Route

Let (L_{\gamma,1}^{(N)}) denote the optimal finite-rank one-dimensional
Lieb--Thirring constant for the first (N) negative eigenvalues. The dual
exponents are related by

\[
p=\frac{\gamma+\frac12}{\gamma-\frac12},
\qquad
\gamma=\frac{p+1}{2(p-1)}.
\]

Thus (2<p<3) corresponds to (1<\gamma<3/2). A sufficiently strong route
to Conjecture 5 is to prove

\[
L_{\gamma,1}^{(N)}=L_{\gamma,1}^{(1)}
\qquad
\text{for all }N\geq1,
\quad 1<\gamma\leq\frac32.
\]

This spectral statement is stronger than the NLS conjecture; it should not be
treated as a currently established equivalence.

## 6. Main Open Subproblems

1. Prove (J_p(2)=2J_p(1)) and non-attainment for the full interval
   (2<p<3).
2. Exclude strict binding for every proper cluster size when (N\geq3).
3. Establish the global lower bound (J_p(N)\geq N J_p(1)) uniformly in
   (N).
4. Characterize minimizing sequences and prove complete separation into
   (N) one-particle solitons.
5. Determine whether finite-rank Lieb--Thirring methods can prove the needed
   lower bound without resolving the stronger full spectral conjecture.

## 7. References

- D. Gontier, M. Lewin, and F. Q. Nazar,
  [The nonlinear Schrödinger equation for orthonormal functions: I. Existence
  of ground states](https://arxiv.org/abs/2002.04963), especially Conjecture 5.
- R. L. Frank, D. Gontier, and M. Lewin,
  [The nonlinear Schrödinger equation for orthonormal functions: II.
  Application to Lieb--Thirring inequalities](https://arxiv.org/abs/2002.04964).
- B. Chen, Y. Guo, Y. Luo, and J. Wei,
  [Ground States of One-Dimensional Fermionic Schrödinger Systems Near a
  Critical Exponent](https://arxiv.org/abs/2604.17363), Theorem 1.1 and
  Proposition 1.2.
- R. L. Frank, D. Gontier, and M. Lewin,
  [Optimizers for the finite-rank Lieb--Thirring
  inequality](https://arxiv.org/abs/2109.05984).
- Y. Guo, Y. Luo, and J. Wei,
  [Complete Classification and Nondegeneracy of N-Component Cubic Nonlinear
  Schrödinger System in R](https://arxiv.org/abs/2606.16544).
