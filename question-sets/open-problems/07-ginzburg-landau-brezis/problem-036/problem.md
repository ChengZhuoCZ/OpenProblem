---
id: problem-036
title: "Global minimality of the radial Ginzburg-Landau vortex on the disk"
primary_category: "Ginzburg-Landau 方程"
secondary_categories:
  - "变分法"
  - "全局极小性"
status: "scoped"
created: "2026-08-06"
language: "mixed zh/en"
source:
  title: "Some of My Favorite Open Problems"
  author: "Haim Brezis"
  locator: "Open Problem 2.2"
  url: "https://ems.press/journals/rlm/articles/13272471"
keywords:
  - Ginzburg-Landau energy
  - global minimizer
  - radial vortex
  - unit disk
  - calculus of variations
---

# Problem 036 - Global Minimality of the Radial Ginzburg-Landau Vortex on the Disk

## Source

This is Brezis Open Problem 2.2 from "Some of My Favorite Open Problems".

## Problem Statement

For \(u\in H^1_g(B_1;\mathbb R^2)\), \(g(x)=x\) on \(\partial B_1\), define

\[
E_\varepsilon(u)
=\frac12\int_{B_1}|\nabla u|^2
+\frac{1}{4\varepsilon^2}\int_{B_1}(|u|^2-1)^2.
\]

Is the radial solution

\[
U_\varepsilon(x)=\frac{x}{|x|}f_\varepsilon(|x|)
\]

a global minimizer of \(E_\varepsilon\) on \(H^1_g(B_1;\mathbb R^2)\) for every \(\varepsilon>0\)?

Equivalently, is

\[
E_\varepsilon(u)\ge E_\varepsilon(U_\varepsilon)
\qquad
\forall u\in H^1_g(B_1;\mathbb R^2)?
\]

## Known Context

- This is weaker than the full uniqueness problem: uniqueness of all critical points would imply global minimality.
- The radial solution is a strict local minimizer for every \(\varepsilon>0\).
- The answer is positive in the small-\(\varepsilon\) and large-\(\varepsilon\) regimes inherited from known uniqueness results.
- The two-dimensional intermediate regime remains open.
- In higher dimensions, uniqueness/global minimality results exist under dimension or structural assumptions, but they do not directly settle the original two-dimensional disk problem.

## Data Still Needed

- Identify a possible global calibration, rearrangement, or defect decomposition.
- Determine whether high-dimensional Hardy-type methods have a two-dimensional analogue.
