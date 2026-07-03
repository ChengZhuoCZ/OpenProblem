---
id: problem-016
title: "Hyperbolic cross maximal inequality"
primary_category: "调和分析"
secondary_categories:
  - "maximal functions"
  - "Fourier multipliers"
status: "raw"
created: "2026-07-03"
language: "mixed zh/en"
source:
  title: "Some Problems in Harmonic Analysis"
  url: "https://grafakos.missouri.edu/preprints/Problems6.pdf"
  source_problem_number: 11
  contributor: "Andreas Seeger"
keywords:
  - hyperbolic cross
  - maximal inequality
  - Fourier multipliers
  - Riesz means
---

# Problem 016 - Hyperbolic Cross Maximal Inequality

## Source

This is Problem 11 from "Some Problems in Harmonic Analysis", contributed by Andreas Seeger.

## Problem Statement

Let \(\Phi\in C_c^\infty(\mathbb R)\) with \(\Phi(0)\ne 0\), and define multipliers \(T_t\) on \(\mathbb R^2\) by

\[
\widehat{T_t f}(\xi)=\Phi(t^{-1}\xi_1^2\xi_2^2)\widehat f(\xi).
\]

Determine whether there exists \(p\in(1,\infty)\) such that

\[
\left\|\sup_{k\in\mathbb Z}|T_{2^k}f|\right\|_{L^p(\mathbb R^2)}
\le C\|f\|_{L^p(\mathbb R^2)}.
\]

## Background

An affirmative result for one \(p\) would imply the full \(1<p<\infty\) range by Calderon-Zygmund methods and would address related convergence questions for hyperbolic Riesz means.

## Known Context

- Each fixed \(T_t\) is uniformly \(L^p\)-bounded.
- The difficulty is the lacunary maximal operator over \(t=2^k\).

## Data Still Needed

- Verify the exact multiplier normalization.
- Compile known maximal multiplier results for hyperbolic crosses.
