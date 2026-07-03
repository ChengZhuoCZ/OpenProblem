---
id: problem-018
title: "Triangular Hilbert transform"
primary_category: "调和分析"
secondary_categories:
  - "time-frequency analysis"
  - "multilinear analysis"
status: "raw"
created: "2026-07-03"
language: "mixed zh/en"
source:
  title: "Some Problems in Harmonic Analysis"
  url: "https://grafakos.missouri.edu/preprints/Problems6.pdf"
  source_problem_number: 13
  contributor: "Christoph Thiele"
keywords:
  - triangular Hilbert transform
  - simplex Hilbert transform
  - multilinear singular integrals
  - dyadic models
---

# Problem 018 - Triangular Hilbert Transform

## Source

This is Problem 13 from "Some Problems in Harmonic Analysis", contributed by Christoph Thiele.

## Problem Statement

For the triangular Hilbert transform form

\[
\Lambda_3(f,g,h)
=\operatorname{p.v.}\int\int\int
\frac{f(x,y)g(y,z)h(z,x)}{x+y+z}\,dx\,dy\,dz,
\]

prove the a priori estimate

\[
|\Lambda_3(f,g,h)|
\le C\|f\|_{L^3}\|g\|_{L^3}\|h\|_{L^3}.
\]

## Background

The triangular Hilbert transform is a central degree-three member of the simplex Hilbert transform family. The degree-two case reduces to the classical Hilbert transform, while higher degrees appear far beyond current methods.

## Known Context

- Any bounded estimate with exponents \(p,q,r\) satisfying \(1/p+1/q+1/r=1\) would imply the symmetric \(L^3\) estimate by permutation and interpolation.
- Dyadic models and truncated growth estimates provide partial evidence and test cases.

## Data Still Needed

- Separate the continuous problem, dyadic model, and truncated estimates in the progress tracker.
- Check the latest bounds after the source PDF.
