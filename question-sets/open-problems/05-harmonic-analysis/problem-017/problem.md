---
id: problem-017
title: "Pointwise convergence for rough singular integrals on L1"
primary_category: "调和分析"
secondary_categories:
  - "singular integrals"
status: "raw"
created: "2026-07-03"
language: "mixed zh/en"
source:
  title: "Some Problems in Harmonic Analysis"
  url: "https://grafakos.missouri.edu/preprints/Problems6.pdf"
  source_problem_number: 12
  contributor: "Andreas Seeger"
keywords:
  - rough singular integrals
  - weak type
  - sparse domination
  - pointwise convergence
---

# Problem 017 - Pointwise Convergence for Rough Singular Integrals on \(L^1\)

## Source

This is Problem 12 from "Some Problems in Harmonic Analysis", contributed by Andreas Seeger.

## Problem Statement

Let \(d\ge 2\), \(q>1\), and \(\Omega\in L^q(S^{d-1})\) have mean zero. Define truncated rough singular integrals

\[
T_\varepsilon f(x)=
\int_{\varepsilon<|y|\le 1}|y|^{-d}\Omega(y/|y|)f(x-y)\,dy.
\]

For \(f\in L^1(\mathbb R^d)\), does \(\lim_{\varepsilon\to 0}T_\varepsilon f(x)\) exist for almost every \(x\)?

Equivalently, is the maximal truncation \(\sup_{0<\varepsilon<1}|T_\varepsilon f|\) of weak type \((1,1)\)?

## Background

Uniform weak type \((1,1)\) bounds for each fixed truncation are known, but the maximal truncation and almost-everywhere convergence question remain open in this formulation.

## Known Context

- The source connects the problem to sparse domination and weighted inequalities for rough singular integrals.
- Earlier work provides low-dimensional and stratified-group variants.

## Data Still Needed

- Check whether post-2016 sparse domination results settle any cases.
- Record exact assumptions on \(\Omega\) needed for current best partial results.
