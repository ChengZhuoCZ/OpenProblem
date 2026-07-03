---
id: problem-014
title: "Polarization constants for fat Cantor sets"
primary_category: "调和分析"
secondary_categories:
  - "势论"
  - "几何测度论"
status: "raw"
created: "2026-07-03"
language: "mixed zh/en"
source:
  title: "Some Problems in Harmonic Analysis"
  url: "https://grafakos.missouri.edu/preprints/Problems6.pdf"
  source_problem_number: 9
  contributor: "Alexander Reznikov"
keywords:
  - polarization constants
  - fat Cantor sets
  - Riesz potentials
  - asymptotics
---

# Problem 014 - Polarization Constants for Fat Cantor Sets

## Source

This is Problem 9 from "Some Problems in Harmonic Analysis", contributed by Alexander Reznikov.

## Problem Statement

Let \(C\subset[0,1]\) be a fat Cantor set with positive Lebesgue measure \(m_1(C)>0\), and fix \(s>1\). For \(N\)-point multisets \(\omega_N\subset C\), define the Riesz polarization quantity \(P_s(C;N)\) as in the source.

Prove that

\[
\lim_{N\to\infty}\frac{P_s(C;N)}{N^s}
\]

exists. Further, decide whether

\[
\lim_{N\to\infty}\frac{P_s(C;N)}{N^s}
=
\frac{2(2s-1)\zeta(s)}{m_1(C)^s}.
\]

## Background

The source compares this conjectural asymptotic with the known formula for the circle, where the numerator is the same and the denominator is the length to the power \(s\).

## Known Context

- Two-sided bounds of order \(N^s\) are known.
- The open issue is existence and identification of the sharp asymptotic constant.

## Data Still Needed

- Write the exact definition of \(P_s(C;\omega_N)\) with all quantifiers and multiplicities.
- Choose a concrete fat Cantor set for experimentation.
