---
id: problem-005
title: "Entire Alexandrov solutions of the Monge-Ampère equation with prescribed density"
primary_category: "完全非线性PDE"
secondary_categories:
  - "凸几何及相关问题"
status: "theorem-draft"
created: "2026-06-25"
language: "mixed zh/en"
keywords:
  - Monge-Ampere equation
  - Alexandrov solution
  - entire solution
  - convex solution
  - prescribed density
  - global existence
---

# Problem 005 — Entire Alexandrov Solutions of \(\det D^2u=f\)

## 1. Background

Let \(u:\mathbb R^n\to\mathbb R\) be a convex function.
Its Alexandrov Monge--Ampère measure is

\[
M_u(E)=|\partial u(E)|
\]

for Borel sets \(E\subset \mathbb R^n\), where \(\partial u(E)\) is the union of subgradients of \(u\) over \(E\).

We say that \(u\) solves

\[
\det D^2u=f
\]

in the Alexandrov sense if

\[
M_u=f(x)\,dx.
\]

The question is whether an arbitrary positive density \(f>1\) on the whole space \(\mathbb R^n\) can be realized as the Monge--Ampère measure of an entire convex function.

---

## 2. Main Theorem Form

### Target Theorem: Global Alexandrov Existence

Let

\[
f:\mathbb R^n\to(1,\infty)
\]

be a prescribed density. After imposing the minimal necessary assumptions, for example

\[
f\in L^1_{\mathrm{loc}}(\mathbb R^n),
\]

prove that there exists a convex Alexandrov solution

\[
u:\mathbb R^n\to\mathbb R
\]

such that

\[
\boxed{
M_u=f(x)\,dx
\quad\text{on }\mathbb R^n.
}
\]

Equivalently,

\[
\boxed{
\det D^2u=f
\quad\text{in the Alexandrov sense on }\mathbb R^n.
}
\]

One may normalize the solution by

\[
u(0)=0,
\qquad
0\in\partial u(0).
\]

---

## 3. Stronger Global-Asymptotic Form

A more rigid version asks whether one can impose a prescribed quadratic asymptotic:

\[
u(x)
=
\frac12 x^TAx+o(|x|^2)
\quad\text{as } |x|\to\infty,
\]

with

\[
\det A = \text{appropriate average density}.
\]

This stronger formulation generally requires additional global assumptions on \(f\), such as periodicity, convergence to a constant, or an asymptotic average.

---

## 4. Counterexample Form

A counterexample to the unrestricted statement would be a density \(f>1\) for which no finite convex function \(u:\mathbb R^n\to\mathbb R\) has

\[
M_u=f(x)\,dx.
\]

If one imposes a quadratic asymptotic, a counterexample may arise from a density \(f\) whose large-scale mass distribution is incompatible with the chosen asymptotic matrix \(A\).

---

## 5. Weaker Improvement Forms

Possible weaker targets:

1. prove existence for \(f\in L^\infty_{\mathrm{loc}}\) with \(1\le f\le C\);
2. prove existence for periodic \(f\);
3. prove existence for \(f\to1\) at infinity;
4. characterize exactly which locally finite measures \(\mu=f\,dx\) arise as \(M_u\) for finite convex \(u\) on all of \(\mathbb R^n\);
5. construct explicit examples or obstructions in low dimensions.

---

## 6. Original Statement

> Given a function \(f>1\) defined on entire \(\mathbb R^n\), can we find a convex Alexandrov solution \(u\) such that \(\det D^2u=f\) on \(\mathbb R^n\)?
