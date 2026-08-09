---
id: problem-042
title: "BV regularity of the gradient of ROF minimizers"
primary_category: "全变差正则化与 ROF"
secondary_categories:
  - "BV functions"
  - "calculus of variations"
  - "image processing"
  - "regularity theory"
status: "scoped"
created: "2026-08-09"
language: "mixed zh/en"
source:
  title: "Some of My Favorite Open Problems"
  author: "Haïm Brezis"
  locator: "Open Problem 8.1"
  url: "https://ems.press/journals/rlm/articles/13272471"
keywords:
  - Rudin-Osher-Fatemi
  - total variation
  - BV regularity
  - gradient
  - denoising
---

# Problem 042 - BV Regularity of the Gradient of ROF Minimizers

## Source

This is Brezis Open Problem 8.1 from *Some of My Favorite Open Problems*.

## Setting

Let \(\Omega\subset\mathbb R^N\) be a smooth bounded domain with \(N\ge2\), and let \(f\) be smooth. Consider the Rudin--Osher--Fatemi functional

\[
\Phi(u)=|Du|(\Omega)+\frac12\int_\Omega |u-f|^2\,dx
\]

on \(BV(\Omega)\cap L^2(\Omega)\). Let \(U\) be its unique minimizer.

## Problem Statement

Does

\[
\nabla U\in BV(\Omega)
\]

hold in dimensions \(N\ge2\)?

## Known Boundary

- The established first-order regularity is \(\nabla U\in L^\infty(\Omega)\), while \(\nabla U\) need not be continuous.
- In one dimension the answer is positive.
- The one-dimensional obstacle-problem transformation used in the positive result does not presently extend to higher dimensions.

## References

- H. Brezis, [*Some of my favorite open problems*](https://sites.math.rutgers.edu/~brezis/PUBlications/234.pdf), Open Problem 8.1.
- H. Brezis, *New approximations of the total variation and filters in imaging*, Atti Accad. Naz. Lincei Rend. Lincei Mat. Appl. 26 (2015), 223--240.
