---
id: problem-002
title: "Fejes Tóth's conjecture on the maximal sum of angles between lines"
primary_category: "离散几何与组合"
secondary_categories:
  - "凸几何及相关问题"
status: "theorem-draft"
created: "2026-06-25"
language: "mixed zh/en"
keywords:
  - Fejes Toth conjecture
  - sum of angles between lines
  - projective space
  - spherical configurations
  - energy maximization
  - discrete geometry
source:
  - "https://www.math.toronto.edu/mccann/papers/LimMcCann20a.pdf"
---

# Problem 002 — Fejes Tóth's Conjecture on the Sum of Angles Between Lines

## 1. Background

Let \(L_1,\dots,L_N\) be \(N\) unoriented lines through the origin in \(\mathbb R^{d+1}\).
Equivalently, choose representatives \(x_i\in S^d\), with the identification \(x_i\sim -x_i\).

The non-obtuse angle between two unoriented lines is

\[
\theta(L_i,L_j)
=
\arccos |\langle x_i,x_j\rangle|
\in [0,\pi/2].
\]

It is often convenient to use the normalized kernel

\[
\Lambda(x,y)
=
\frac{2}{\pi}\arccos |\langle x,y\rangle|
\in [0,1].
\]

The corresponding discrete energy is

\[
E_1(x_1,\dots,x_N)
=
\sum_{1\le i<j\le N}
\Lambda(x_i,x_j),
\]

or equivalently the unnormalized sum

\[
S_N(L_1,\dots,L_N)
=
\sum_{1\le i<j\le N}
\theta(L_i,L_j).
\]

Fejes Tóth's problem asks for the configurations of \(N\) lines maximizing this angle sum.

The conjectured optimizer is the configuration obtained by distributing the \(N\) lines as evenly as possible among the \(d+1\) coordinate axes of an orthonormal basis.

---

## 2. Main Theorem Form

### Target Theorem: Fejes Tóth's Conjecture

Let \(d\ge 2\) and \(N\ge 1\).
Among all \(N\) unoriented lines \(L_1,\dots,L_N\) through the origin in \(\mathbb R^{d+1}\),

\[
\boxed{
S_N(L_1,\dots,L_N)
\le
S_N(L_1^\ast,\dots,L_N^\ast),
}
\]

where \(L_1^\ast,\dots,L_N^\ast\) are distributed as evenly as possible among the \(d+1\) mutually orthogonal coordinate axes.

Equivalently, if

\[
N=q(d+1)+r,\qquad 0\le r<d+1,
\]

then the maximizing configuration consists of \(r\) coordinate axes carrying \(q+1\) lines and \(d+1-r\) coordinate axes carrying \(q\) lines.

A sharpened uniqueness form asks that every maximizer is of this form, up to an orthogonal transformation of \(\mathbb R^{d+1}\) and the antipodal identification \(x\sim -x\).

---

## 3. Energy-Exponent Reformulation

For \(\alpha>0\), define

\[
E_\alpha(x_1,\dots,x_N)
=
\sum_{1\le i<j\le N}
\Lambda(x_i,x_j)^\alpha.
\]

A strengthened target is:

\[
\boxed{
E_\alpha(x_1,\dots,x_N)
\le
E_\alpha(x_1^\ast,\dots,x_N^\ast)
\quad \text{for every } \alpha>1.
}
\]

In the strongest form, the balanced repeated orthonormal-basis configuration is the unique maximizer for all \(\alpha>1\).

---

## 4. Counterexample Form

A counterexample consists of \(d\ge2\), \(N\ge1\), and a configuration of \(N\) lines such that

\[
S_N(L_1,\dots,L_N)
>
S_N(L_1^\ast,\dots,L_N^\ast).
\]

For the exponentiated version, a counterexample consists of \(\alpha>1\) and a configuration with

\[
E_\alpha(x_1,\dots,x_N)
>
E_\alpha(x_1^\ast,\dots,x_N^\ast).
\]

---

## 5. Weaker Improvement Form

A weaker but still useful goal is to improve known upper bounds for

\[
\sup_{L_1,\dots,L_N}
S_N(L_1,\dots,L_N)
\]

or for the corresponding energy integral on \(\mathbb{RP}^d\), even without proving the exact optimizer.

---

## 6. Notes from the Source

The cited Lim--McCann paper formulates the conjecture for unoriented lines, embeds it into the family \(E_\alpha\), proves equivalence between the \(\alpha=1\) and \(\alpha>1\) optimizer formulations, and establishes the limiting mild-repulsion case \(\alpha=\infty\).
