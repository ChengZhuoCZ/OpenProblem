---
id: problem-009
title: "Fourier transforms vanishing on the sphere"
primary_category: "调和分析"
secondary_categories:
  - "Fourier analysis"
status: "raw"
created: "2026-07-03"
language: "mixed zh/en"
source:
  title: "Some Problems in Harmonic Analysis"
  url: "https://grafakos.missouri.edu/preprints/Problems6.pdf"
  source_problem_number: 4
  contributor: "Michael Goldberg"
keywords:
  - Fourier restriction
  - Stein-Tomas theorem
  - Bochner-Riesz multipliers
  - Helmholtz equation
---

# Problem 009 - Fourier Transforms Vanishing on the Sphere

## Source

This is Problem 4 from "Some Problems in Harmonic Analysis", contributed by Michael Goldberg.

## Problem Statement

Let \(n\ge 2\). Determine whether there exists

\[
f\in L^{(2n+2)/(n+3)}(\mathbb R^n)
\]

such that

\[
\widehat f|_{S^{n-1}}\equiv 0
\]

but

\[
|1-|\xi|^2|^{-1/2}\widehat f(\xi)\notin L^2(\mathbb R^n).
\]

Equivalently, decide whether vanishing of \(\widehat f\) on the unit sphere is sufficient for the borderline weighted \(L^2\) condition above.

## Background

The Stein-Tomas theorem gives continuity of spherical restrictions in the relevant range. Vanishing on the sphere is necessary for local integrability at the singular surface; the problem asks whether it is sufficient at the endpoint.

## Known Context

- Related sufficient conditions are known for weights \(|1-|\xi|^2|^{-\alpha}\) away from \(\alpha=1/2\).
- In one dimension, Hardy-space type conditions are stronger than simple vanishing.

## Data Still Needed

- Verify the exact endpoint exponent and notation against the source PDF or related papers.
- Identify known post-2016 progress on the endpoint case.
