---
id: problem-004
title: "Unconditional higher-dimensional Hessian estimates for the sigma-2 equation"
primary_category: "完全非线性PDE"
secondary_categories: []
status: "theorem-draft"
created: "2026-06-25"
language: "mixed zh/en"
keywords:
  - sigma-2 equation
  - dimension n greater or equal 5
  - Hessian estimate
  - fully nonlinear PDE
  - Jacobi inequality
  - dynamic semi-convexity
source:
  - "https://sites.math.washington.edu//~yuan/papers/2023aAnnals.pdf"
---

# Problem 004 — Higher-Dimensional \(\sigma_2\) Hessian Estimates

## 1. Background

Consider the Hessian equation

\[
\boxed{
\sigma_2(D^2u)=1
}
\]

in the positive branch

\[
\Delta u>0.
\]

In dimension \(n=4\), the cited Shankar--Yuan work proves interior a priori Hessian estimates and interior regularity.
For dimensions \(n\ge5\), the same paper obtains Hessian estimates under an additional dynamic semi-convexity assumption of the form

\[
\lambda_{\min}(D^2u)
\ge
-c(n)\Delta u.
\]

The open question is whether this extra Hessian-side assumption is genuinely necessary.

---

## 2. Main Theorem Form

### Target Theorem: Unconditional \(n\ge5\) Hessian Estimate

Let \(n\ge5\), and let \(u\) be a smooth solution of

\[
\sigma_2(D^2u)=1
\quad\text{in } B_1(0)\subset\mathbb R^n
\]

in the positive branch

\[
\Delta u>0.
\]

Prove that \(u\) satisfies an interior Hessian estimate

\[
\boxed{
|D^2u(0)|
\le
C(n,\|u\|_{L^\infty(B_1)})
}
\]

or, more generally,

\[
\boxed{
\|D^2u\|_{L^\infty(B_{1/2})}
\le
C(n,\|u\|_{L^\infty(B_1)}).
}
\]

The key point is that no additional convexity, semi-convexity, or dynamic lower bound on \(\lambda_{\min}(D^2u)\) should be assumed.

---

## 3. Regularity Form

A stronger version is:

Every continuous viscosity solution of

\[
\sigma_2(D^2u)=1
\]

in the positive branch in dimension \(n\ge5\) is smooth, or at least

\[
u\in C^{2,\alpha}_{\mathrm{loc}}.
\]

---

## 4. Counterexample Form

A counterexample would consist of a positive-branch solution \(u\) in dimension \(n\ge5\) such that

\[
\sigma_2(D^2u)=1,
\qquad
\Delta u>0,
\]

but \(u\) fails to satisfy any universal interior Hessian estimate depending only on \(n\) and a low-order norm.

A stronger counterexample would be a viscosity solution with a genuine interior singularity.

---

## 5. Weaker Improvement Forms

Possible intermediate goals:

1. prove the Hessian estimate under a weaker assumption than the known dynamic semi-convexity condition;
2. prove that the possible singular set is smaller than currently known;
3. prove a partial regularity theorem with quantitative dimension or capacity bounds;
4. prove unconditional estimates for \(n=5\) first.

---

## 6. Original Statement

> 能否解决 \(n=5\) 或者更高维情形
