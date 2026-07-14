---
id: problem-034
title: "Best quantitative Faber-Krahn constant in the planar convex class"
primary_category: "特征值及相关问题"
secondary_categories:
  - "凸几何及相关问题"
status: "scoped"
created: "2026-07-14"
language: "mixed zh/en"
keywords:
  - Faber-Krahn inequality
  - quantitative stability
  - convex domains
  - first Dirichlet eigenvalue
  - Fraenkel asymmetry
  - explicit constants
---

# Problem 034 - Best Quantitative Faber-Krahn Constant in the Planar Convex Class

## 1. Background

Let

\[
\mathcal K
=
\left\{
\Omega\subset\mathbb R^2:
\Omega\ \text{is a bounded open convex set and }|\Omega|=\pi
\right\}.
\]

Let \(B\subset\mathbb R^2\) be the unit disk. For
\(\Omega\in\mathcal K\), define the first Dirichlet eigenvalue

\[
\lambda_1(\Omega)
=
\inf_{0\neq u\in H_0^1(\Omega)}
\frac{\displaystyle\int_\Omega |\nabla u|^2\,dx}
{\displaystyle\int_\Omega u^2\,dx}.
\]

For the unit disk,

\[
\lambda_1(B)=j_{0,1}^2,
\]

where \(j_{0,1}\) is the first positive zero of the Bessel function
\(J_0\).

Define the normalized Fraenkel asymmetry

\[
\mathcal A(\Omega)
=
\inf_{x\in\mathbb R^2}
\frac{|\Omega\triangle(x+B)|}{\pi}.
\]

The optimal quantitative Faber-Krahn constant in the planar convex class is

\[
\boxed{
C_{2,\mathrm{conv}}^{\mathrm{opt}}
=
\inf_{\substack{\Omega\in\mathcal K\\
\mathcal A(\Omega)>0}}
\frac{\lambda_1(\Omega)-j_{0,1}^2}
{\mathcal A(\Omega)^2}.
}
\]

Known quantitative Faber-Krahn theory gives

\[
C_{2,\mathrm{conv}}^{\mathrm{opt}}>0.
\]

Thus the problem is not to prove mere positivity, but to determine the
sharp constant, or at least a fully explicit computable lower bound.

---

## 2. Problem A: Exact Best Constant

Determine the exact value

\[
\boxed{
C_{2,\mathrm{conv}}^{\mathrm{opt}}.
}
\]

The exact problem includes the following structural questions:

1. Is the infimum attained by a non-disk convex set?
2. If the infimum is not attained, is it approached by convex sets
   \[
   \Omega_k\to B
   \]
   such that
   \[
   \frac{\lambda_1(\Omega_k)-j_{0,1}^2}
   {\mathcal A(\Omega_k)^2}
   \longrightarrow
   C_{2,\mathrm{conv}}^{\mathrm{opt}}?
   \]
3. Does the worst case come from infinitesimal perturbations of the disk,
   or from a family of convex sets far from the disk?
4. Do optimal or asymptotically optimal domains have additional symmetry?

---

## 3. Problem B: Explicit Computable Lower Bound

If the exact value is currently out of reach, prove a completely explicit
estimate

\[
\boxed{
C_{2,\mathrm{conv}}^{\mathrm{opt}}\ge c_{\mathrm{exp}}>0.
}
\]

Equivalently, prove that for every \(\Omega\in\mathcal K\),

\[
\boxed{
\lambda_1(\Omega)-j_{0,1}^2
\ge
c_{\mathrm{exp}}\,\mathcal A(\Omega)^2.
}
\]

Here \(c_{\mathrm{exp}}\) must be genuinely computable. Acceptable forms
include:

1. a specific numerical constant;
2. a closed-form expression involving \(j_{0,1}\), Bessel functions, and
   finitely many elementary constants;
3. a rigorously certified numerical lower bound obtained with explicit
   error control and interval arithmetic.

It is not enough to write \(c_{\mathrm{exp}}=c(2)>0\), or to cite the
existence of a positive dimensional constant without tracking the constants
through the proof.

---

## 4. Equivalent Optimization Formulation

Define

\[
\mathcal Q(\Omega)
=
\frac{\lambda_1(\Omega)-j_{0,1}^2}
{\mathcal A(\Omega)^2}.
\]

The core variational problem is

\[
\boxed{
\inf_{\substack{\Omega\subset\mathbb R^2\\
\Omega\ \text{open and convex},\ |\Omega|=\pi\\
\mathcal A(\Omega)>0}}
\mathcal Q(\Omega).
}
\]

The ideal outcome is an exact value

\[
C_{2,\mathrm{conv}}^{\mathrm{opt}}=C_\ast.
\]

A weaker but still meaningful outcome is a strict two-sided estimate

\[
\boxed{
0<c_-\le C_{2,\mathrm{conv}}^{\mathrm{opt}}\le c_+,
}
\]

where both \(c_-\) and \(c_+\) are explicit computable constants.
The upper bound may come from concrete convex sets or from perturbation
sequences approaching the disk. The main difficulty is a uniform explicit
lower bound \(c_-\) valid for every convex set of area \(\pi\).

---

## 5. First Milestones

1. Collect the sharpest known quantitative Faber-Krahn stability constants
   and identify which are explicit.
2. Separate the planar convex case from the general measurable-set theory.
3. Compute upper bounds using explicit convex competitors, such as ellipses,
   stadium-like convex sets, or controlled perturbations of the disk.
4. Analyze the near-disk shape derivative problem to obtain a candidate
   asymptotic value.
5. Track every constant in a proof of a convex quantitative Faber-Krahn
   inequality and produce a certified value of \(c_{\mathrm{exp}}\).
