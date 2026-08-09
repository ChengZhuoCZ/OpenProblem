---
id: problem-040
title: "Unboundedness of the extremal Gelfand solution on convex domains"
primary_category: "极值解与半线性椭圆方程"
secondary_categories:
  - "半线性椭圆方程"
  - "Gelfand problem"
  - "极值解"
  - "凸域"
status: "scoped"
created: "2026-08-09"
language: "mixed zh/en"
source:
  title: "Some of My Favorite Open Problems"
  author: "Haïm Brezis"
  locator: "Open Problem 6.1"
  url: "https://ems.press/journals/rlm/articles/13272471"
keywords:
  - extremal solution
  - Gelfand equation
  - exponential nonlinearity
  - convex domain
  - singular solution
---

# Problem 040 - Unboundedness of the Extremal Gelfand Solution on Convex Domains

## Source

This is Brezis Open Problem 6.1 from *Some of My Favorite Open Problems*.

## Variational-PDE Setting

Let \(\Omega\subset\mathbb R^N\) be a smooth bounded domain and consider

\[
\begin{cases}
-\Delta u=\lambda f(u) & \text{in }\Omega,\\
u>0 & \text{in }\Omega,\\
u=0 & \text{on }\partial\Omega.
\end{cases}
\]

Under the usual assumptions that \(f(0)>0\), \(f\) is smooth, increasing, convex, and superlinear, there is an extremal parameter \(\lambda^*\) and an extremal weak solution

\[
u^*=\lim_{\lambda\uparrow\lambda^*}u(\lambda).
\]

## Problem Statement

Assume \(N\ge10\), \(\Omega\) is smooth, bounded, and convex, and \(f(u)=e^u\). Must \(u^*\) be unbounded?

If the answer is negative for some such \(\Omega\), can one find another nonlinearity \(f\) satisfying the standard assumptions, possibly depending on \(\Omega\), for which \(u^*\) is unbounded?

## Known Boundary

- For \(N\le9\), extremal solutions are bounded under the standard assumptions.
- For \(N\ge10\) on the unit ball with \(f(u)=e^u\), the Joseph--Lundgren example is singular:
  \[
  u^*(x)=\log\frac{1}{|x|^2}.
  \]
- That radial-ball example does not decide whether every smooth bounded convex domain has an unbounded extremal solution.

## References

- H. Brezis, [*Some of my favorite open problems*](https://sites.math.rutgers.edu/~brezis/PUBlications/234.pdf), Open Problem 6.1.
- X. Cabré, A. Figalli, X. Ros-Oton, and J. Serra, *Stable solutions to semilinear elliptic equations are smooth up to dimension 9*, Acta Math. 224 (2020).
