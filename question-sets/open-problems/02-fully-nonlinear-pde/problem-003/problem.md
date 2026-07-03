---
id: problem-003
title: "Interior C^{2,alpha} estimates for sigma-2 equations with Hölder right-hand side"
primary_category: "完全非线性PDE"
secondary_categories: []
status: "theorem-draft"
created: "2026-06-25"
language: "mixed zh/en"
keywords:
  - sigma-2 equation
  - Hessian equation
  - C2 alpha estimates
  - Evans-Krylov
  - fully nonlinear elliptic equations
  - variable right-hand side
source:
  - "https://sites.math.washington.edu//~yuan/papers/2023aAnnals.pdf"
---

# Problem 003 — \(C^{2,\alpha}\) Estimates for \(\sigma_2(D^2u)=f\)

## 1. Background

Let \(\Omega\subset\mathbb R^n\), and let

\[
\lambda(D^2u)=(\lambda_1,\dots,\lambda_n)
\]

denote the eigenvalues of the Hessian. The second elementary symmetric function is

\[
\sigma_2(D^2u)
=
\sum_{1\le i<j\le n}\lambda_i\lambda_j.
\]

The equation

\[
\sigma_2(D^2u)=f
\]

is a fully nonlinear Hessian equation. The natural elliptic branch is the positive \(\Gamma_2\)-admissible branch, usually requiring

\[
\sigma_1(D^2u)>0,\qquad \sigma_2(D^2u)>0.
\]

The constant right-hand-side equation

\[
\sigma_2(D^2u)=1
\]

has recently been understood in dimension \(n=4\) at the level of interior Hessian estimates and interior regularity. The open direction here is to replace the constant right-hand side by a Hölder function

\[
0<f\in C^\alpha.
\]

---

## 2. Main Theorem Form

### Target Theorem: Interior \(C^{2,\alpha}\) Estimate for Variable RHS

Let \(\Omega\subset\mathbb R^4\), \(0<\alpha<1\), and let \(u\) be a \(\Gamma_2\)-admissible solution of

\[
\boxed{
\sigma_2(D^2u)=f(x)
\quad\text{in }\Omega,
}
\]

where

\[
0<\lambda\le f\le \Lambda,
\qquad
f\in C^\alpha(\Omega).
\]

For every compactly contained subdomain \(\Omega'\Subset \Omega\), prove an a priori estimate

\[
\boxed{
\|u\|_{C^{2,\alpha}(\Omega')}
\le
C
}
\]

where \(C\) depends only on

\[
\alpha,\ \lambda,\ \Lambda,\ \|f\|_{C^\alpha(\Omega)},\
\operatorname{dist}(\Omega',\partial\Omega),
\]

and an appropriate low-order norm of \(u\), for example \(\|u\|_{L^\infty(\Omega)}\) or \(\|u\|_{C^1(\Omega)}\).

---

## 3. Viscosity/Alexandrov Regularity Form

A stronger form is:

If \(u\) is a continuous \(\Gamma_2\)-admissible viscosity solution of

\[
\sigma_2(D^2u)=f(x),
\qquad
0<f\in C^\alpha,
\]

then

\[
u\in C^{2,\alpha}_{\mathrm{loc}}(\Omega).
\]

---

## 4. Counterexample Form

A counterexample would consist of a positive Hölder function \(f\in C^\alpha\) and a \(\Gamma_2\)-admissible solution \(u\) such that

\[
\sigma_2(D^2u)=f
\]

but \(u\notin C^{2,\alpha}_{\mathrm{loc}}\), or such that no estimate of the above form can hold with only the stated data.

---

## 5. Weaker Improvement Forms

Possible weaker targets include:

1. an interior \(C^2\) or \(C^{1,1}\) estimate under \(f\in C^\alpha\);
2. an estimate \(u\in C^{2,\beta}_{\mathrm{loc}}\) for some \(0<\beta<\alpha\);
3. the theorem under stronger assumptions such as \(f\in C^{1,1}\);
4. the theorem under a dynamic semi-convexity or convexity assumption on \(D^2u\).

---

## 6. Original Statement

> 能否建立 \(\sigma_2(D^2u)=f,\ 0<f\in C^{\alpha}\) 的 \(u\) 的 \(C^{2,\alpha}\) 估计
