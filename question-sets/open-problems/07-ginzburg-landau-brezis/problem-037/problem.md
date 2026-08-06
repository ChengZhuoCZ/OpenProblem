---
id: problem-037
title: "Asymptotic radialization for p-Ginzburg-Landau minimizers"
primary_category: "Ginzburg-Landau 方程"
secondary_categories:
  - "p-Laplace 型方程"
  - "奇异极限"
status: "scoped"
created: "2026-08-06"
language: "mixed zh/en"
source:
  title: "Some of My Favorite Open Problems"
  author: "Haim Brezis"
  locator: "Open Problem 2.3"
  url: "https://ems.press/journals/rlm/articles/13272471"
keywords:
  - p-Ginzburg-Landau
  - asymptotic symmetry
  - vortex limit
  - p greater than 2
  - critical points
---

# Problem 037 - Asymptotic Radialization for \(p\)-Ginzburg-Landau Minimizers

## Source

This is Brezis Open Problem 2.3 from "Some of My Favorite Open Problems".

## Problem Statement

For \(p>1\), define

\[
E_{\varepsilon,p}(u)
=\frac1p\int_{B_1}|\nabla u|^p
+\frac{1}{4\varepsilon^2}\int_{B_1}(|u|^2-1)^2
\]

on \(W^{1,p}_g(B_1;\mathbb R^2)\), with \(g(x)=x\) on \(\partial B_1\).

For \(p>2\), let \(u_\varepsilon\) be a global minimizer, or more strongly an arbitrary critical point. Does

\[
u_\varepsilon(x)\to \frac{x}{|x|}
\]

hold in \(B_1\setminus\{0\}\) as \(\varepsilon\to0\), in a suitable local sense?

## Known Context

- For \(p<2\), the minimizer version is known to be positive.
- For \(p=2\), both minimizer and critical-point versions are known to be positive.
- For \(p>2\), both versions remain open.
- Radial minimizers are known in the radial class, with local stability results in part of the range, but this does not exclude nonradial minimizers or critical points.

## Data Still Needed

- Specify the precise convergence topology: local uniform convergence, \(W^{1,q}_{\mathrm{loc}}\), or another natural local topology.
- Separate the global minimizer version from the much stronger arbitrary critical-point version.
- Understand how the vortex core scales when \(p>2\), since \(x/|x|\notin W^{1,p}(B_1)\).
