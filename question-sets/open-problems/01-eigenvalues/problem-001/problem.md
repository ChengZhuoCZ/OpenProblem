---
id: problem-001
title: "Optimal Pleijel constant problem"
primary_category: "特征值及相关问题"
secondary_categories: []
status: "theorem-draft"
created: "2026-06-25"
language: "mixed zh/en"
keywords:
  - eigenvalues
  - nodal domains
  - Courant theorem
  - Pleijel theorem
  - optimal constant
  - counterexample
---

# Problem 001 — Optimal Pleijel Constant Problem

## 1. Background

Let \(\Omega \subset \mathbb{R}^d\) be an admissible bounded domain, and consider the eigenvalue problem

\[
-\Delta u_k=\lambda_k u_k
\quad \text{in } \Omega,
\]

with the prescribed boundary condition, usually Dirichlet unless otherwise specified.
Let

\[
\nu(u_k)
\]

denote the number of nodal domains of the eigenfunction \(u_k\).

Courant's nodal domain theorem gives the universal bound

\[
\nu(u_k)\le k.
\]

Pleijel's theorem improves this asymptotically: there exists a constant

\[
C_{\mathrm{Pl}}(d)<1
\]

such that

\[
\limsup_{k\to\infty}\frac{\nu(u_k)}{k}
\le C_{\mathrm{Pl}}(d).
\]

In dimension \(d=2\), the classical Pleijel constant is

\[
C_{\mathrm{Pl}}(2)=\frac{4}{j_{0,1}^{2}},
\]

where \(j_{0,1}\) is the first positive zero of the Bessel function \(J_0\).

The problem is to determine whether the known Pleijel-type constant is optimal in the chosen setting, or whether it can be improved.

---

## 2. Main Theorem Form

### Target Theorem: Optimal Pleijel Constant

Fix a class of admissible domains \(\mathcal A\), a dimension \(d\), and a boundary condition.
There exists an optimal constant

\[
C_\ast=C_\ast(\mathcal A,d,\text{boundary condition})<1
\]

such that for every \(\Omega\in\mathcal A\) and every relevant sequence of eigenfunctions \(\{u_k\}\),

\[
\boxed{
\limsup_{k\to\infty}\frac{\nu(u_k)}{k}
\le C_\ast .
}
\]

Moreover, the constant \(C_\ast\) is sharp: for every \(\varepsilon>0\), there exist admissible examples \(\Omega\in\mathcal A\) and eigenfunctions \(u_{k_j}\) such that

\[
\limsup_{j\to\infty}\frac{\nu(u_{k_j})}{k_j}
\ge C_\ast-\varepsilon.
\]

---

## 3. Counterexample Form

If a proposed constant \(C_{\mathrm{cand}}\) is conjectured to be optimal, then a counterexample would consist of an admissible domain \(\Omega\in\mathcal A\), a subsequence of eigenfunctions \(u_{k_j}\), and a number \(\delta>0\), such that

\[
\boxed{
\limsup_{j\to\infty}
\frac{\nu(u_{k_j})}{k_j}
\ge C_{\mathrm{cand}}+\delta .
}
\]

This would disprove the proposed Pleijel-type bound in the chosen setting.

---

## 4. Weaker Improvement Form

A weaker but still meaningful goal is to prove that the currently known Pleijel constant is not sharp, by finding an explicit improvement

\[
\delta>0
\]

such that for all \(\Omega\in\mathcal A\),

\[
\boxed{
\limsup_{k\to\infty}\frac{\nu(u_k)}{k}
\le C_{\mathrm{Pl}}(d)-\delta .
}
\]

In dimension \(d=2\), this would take the form

\[
\limsup_{k\to\infty}\frac{\nu(u_k)}{k}
\le
\frac{4}{j_{0,1}^{2}}-\delta.
\]

---

## 5. Original Statement

> we wanna prove the optimal constant/find a counterexample, or at least improving the pleitjel constant

Here `pleitjel` is interpreted as `Pleijel`.

---

## 6. Data Still Needed for a Complete Problem Statement

To make the theorem fully precise, one must specify:

1. the dimension \(d\);
2. the operator, for example Dirichlet Laplacian, Neumann Laplacian, magnetic Laplacian, Schrödinger operator, or another elliptic operator;
3. the admissible domain class \(\mathcal A\);
4. whether eigenvalue multiplicities are handled by arbitrary eigenfunctions, generic domains, or chosen eigenbases;
5. the currently conjectured or known candidate constant \(C_{\mathrm{cand}}\).
