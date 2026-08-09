---
id: problem-041
title: "Blow-up set of unbounded extremal solutions"
primary_category: "极值解与半线性椭圆方程"
secondary_categories:
  - "半线性椭圆方程"
  - "极值解"
  - "奇异集"
  - "凸域"
status: "scoped"
created: "2026-08-09"
language: "mixed zh/en"
source:
  title: "Some of My Favorite Open Problems"
  author: "Haïm Brezis"
  locator: "Open Problem 6.2"
  url: "https://ems.press/journals/rlm/articles/13272471"
keywords:
  - extremal solution
  - blow-up set
  - singular set
  - stable semilinear equation
  - convex domain
---

# Problem 041 - Blow-up Set of Unbounded Extremal Solutions

## Source

This is Brezis Open Problem 6.2 from *Some of My Favorite Open Problems*.

## Setting

Use the extremal solution \(u^*\) associated with

\[
\begin{cases}
-\Delta u=\lambda f(u) & \text{in }\Omega,\\
u>0 & \text{in }\Omega,\\
u=0 & \text{on }\partial\Omega,
\end{cases}
\]

where \(f\) is positive, increasing, convex, and superlinear.

## Problem Statement

Assume that \(u^*\) is unbounded. What can be said about its blow-up (singular) set \(\Sigma(u^*)\)? In particular, when \(\Omega\) is convex, must this set consist of a single point?

## Verified Partial Results

For stable solutions with \(f(t)=e^t\), one has the quantitative bound

\[
\dim_{\mathcal H}\Sigma(u)\le N-10.
\]

This does not imply that \(\Sigma(u^*)\) is a singleton in a convex domain: a set of Hausdorff dimension at most zero may contain more than one point.

## References

- H. Brezis, [*Some of my favorite open problems*](https://sites.math.rutgers.edu/~brezis/PUBlications/234.pdf), Open Problem 6.2.
- A. Figalli and F. Franceschini, [*Stable Semilinear Elliptic Equations: \(\varepsilon\)-Regularity à la Brezis and Dimensional Bounds for the Singular Set*](https://arxiv.org/abs/2606.21546), 2026 preprint.
- K. Wang, *Partial regularity of stable solutions to the Emden equation*, Calc. Var. PDE 44 (2012), 601--610.
