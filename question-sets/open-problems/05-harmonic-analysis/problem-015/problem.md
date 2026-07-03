---
id: problem-015
title: "Convolutions with radial kernels"
primary_category: "调和分析"
secondary_categories:
  - "Fourier multipliers"
status: "raw"
created: "2026-07-03"
language: "mixed zh/en"
source:
  title: "Some Problems in Harmonic Analysis"
  url: "https://grafakos.missouri.edu/preprints/Problems6.pdf"
  source_problem_number: 10
  contributor: "Andreas Seeger"
keywords:
  - radial kernels
  - local smoothing
  - Fourier multipliers
  - cone multipliers
---

# Problem 015 - Convolutions with Radial Kernels

## Source

This is Problem 10 from "Some Problems in Harmonic Analysis", contributed by Andreas Seeger.

## Problem Statement

Let \(\sigma_r\) denote surface measure on the radius-\(r\) sphere in \(\mathbb R^d\), and let \(\eta\in\mathcal S(\mathbb R^d)\) have Fourier transform vanishing near the origin.

For \(1<p<2\) in the dimensional range stated in the source, prove the endpoint convolution estimate

\[
\left\|\int_1^\infty (\eta*\sigma_r*g)(\cdot,r)\,dr\right\|_{L^p(\mathbb R^d)}
\le C(p,d,\eta)
\left(\int_1^\infty\int_{\mathbb R^d}|g(x,r)|^p\,dx\,r^{d-1}\,dr\right)^{1/p}.
\]

## Background

The inequality implies effective characterizations of radial Fourier multipliers and has consequences for local smoothing, Bochner-Riesz, restriction, and Kakeya-Nikodym type problems.

## Known Context

- The estimate is trivial for \(p=1\).
- Nontrivial ranges are known in high dimensions and weaker weighted forms follow from decoupling.

## Data Still Needed

- Verify the exact dimensional condition \(d>p/(2-p)\) from the source layout.
- Record known improvements after the source PDF.
