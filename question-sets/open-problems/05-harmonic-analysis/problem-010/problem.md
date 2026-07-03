---
id: problem-010
title: "Regularity or blow-up for the De Gregorio model"
primary_category: "调和分析"
secondary_categories:
  - "偏微分方程"
  - "流体方程"
status: "raw"
created: "2026-07-03"
language: "mixed zh/en"
source:
  title: "Some Problems in Harmonic Analysis"
  url: "https://grafakos.missouri.edu/preprints/Problems6.pdf"
  source_problem_number: 5
  contributor: "Alexander Kiselev"
keywords:
  - De Gregorio model
  - Euler equation
  - vorticity
  - Hilbert transform
  - blow-up
---

# Problem 010 - Regularity or Blow-Up for the De Gregorio Model

## Source

This is Problem 5 from "Some Problems in Harmonic Analysis", contributed by Alexander Kiselev.

## Problem Statement

Study the one-dimensional De Gregorio model

\[
\partial_t\omega+u\partial_x\omega=\omega\partial_x u,\qquad \partial_xu=H\omega,
\]

with periodic or otherwise natural initial data. Determine whether solutions remain globally regular or can blow up in finite time.

## Background

The model combines a transport term with the stretching mechanism from the Constantin-Lax-Majda model. The source asks whether nonlinear advection can cancel the blow-up mechanism suggested by the simpler model.

## Known Context

- The transport-only analogue behaves like two-dimensional Euler.
- The Constantin-Lax-Majda model without transport has explicit finite-time blow-up examples.
- Numerical simulations cited in the source suggest global regularity for the full De Gregorio model.

## Data Still Needed

- Decide the function class and domain for the first formulation.
- Check known progress after 2016 on global regularity or blow-up.
