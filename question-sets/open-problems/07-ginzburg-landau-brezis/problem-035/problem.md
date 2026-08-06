---
id: problem-035
title: "Uniqueness of the radial Ginzburg-Landau solution on the disk"
primary_category: "Ginzburg-Landau 方程"
secondary_categories:
  - "椭圆方程"
  - "对称性与唯一性"
status: "scoped"
created: "2026-08-06"
language: "mixed zh/en"
source:
  title: "Some of My Favorite Open Problems"
  author: "Haim Brezis"
  locator: "Open Problem 2.1"
  url: "https://ems.press/journals/rlm/articles/13272471"
keywords:
  - Ginzburg-Landau equation
  - uniqueness
  - radial symmetry
  - vortex
  - unit disk
---

# Problem 035 - Uniqueness of the Radial Ginzburg-Landau Solution on the Disk

## Source

This is Brezis Open Problem 2.1 from "Some of My Favorite Open Problems".

## Problem Statement

Let \(\Omega=B_1(0)\subset\mathbb R^2\), and consider

\[
\begin{cases}
-\Delta u=\varepsilon^{-2}u(1-|u|^2),& x\in\Omega,\\
u(x)=x,& x\in\partial\Omega,
\end{cases}
\]

where \(u:\Omega\to\mathbb R^2\) and \(\varepsilon>0\).

There is a standard radial solution

\[
U_\varepsilon(x)=\frac{x}{|x|}f_\varepsilon(|x|),
\]

where \(f_\varepsilon\) solves

\[
\begin{cases}
-f''-\dfrac1r f'+\dfrac1{r^2}f
=\varepsilon^{-2}f(1-f^2),&0<r<1,\\
f(0)=0,\qquad f(1)=1.
\end{cases}
\]

Is \(U_\varepsilon\) the unique solution for every \(\varepsilon>0\)?

Equivalently, must every solution inherit the radial symmetry of the boundary data?

## Known Context

- The answer is known to be positive for \(\varepsilon\) sufficiently small.
- The answer is also positive for \(\varepsilon\ge \lambda_1(B_1)^{-1/2}\), where the energy is strictly convex.
- The intermediate range remains open.
- The radial solution has positive second variation and is a strict local minimizer for every \(\varepsilon>0\).

## Data Still Needed

- Record the exact small-\(\varepsilon\) result of Pacard-Riviere.
- Track whether the intermediate range admits bifurcation, degree-theoretic, or global continuation obstructions.
