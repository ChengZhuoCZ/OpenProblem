---
id: problem-021
title: "Geometric conditions for lacunary maximal functions on convex curves"
primary_category: "调和分析"
secondary_categories:
  - "maximal functions"
  - "凸几何及相关问题"
status: "raw"
created: "2026-07-03"
language: "mixed zh/en"
source:
  title: "Some Problems in Harmonic Analysis"
  url: "https://grafakos.missouri.edu/preprints/Problems6.pdf"
  source_problem_number: 16
  contributor: "James Wright"
keywords:
  - lacunary maximal functions
  - convex curves
  - cap geometry
  - Fourier decay
---

# Problem 021 - Geometric Conditions for Lacunary Maximal Functions on Convex Curves

## Source

This is Problem 16 from "Some Problems in Harmonic Analysis", contributed by James Wright.

## Problem Statement

Let \(\Omega\subset\mathbb R^2\) be a bounded convex domain containing the origin, and let \(\sigma\) be arclength measure on \(\partial\Omega\). Consider

\[
Mf(x)=\sup_{k\in\mathbb Z}\left|\int_{\partial\Omega}f(x-2^k y)\,d\sigma(y)\right|.
\]

For fixed \(1<p<\infty\), find a necessary and sufficient geometric condition on \(\partial\Omega\) guaranteeing \(L^p(\mathbb R^2)\)-boundedness of \(M\).

The source highlights the candidate cap condition

\[
\sup_{\theta\in S^1}\int_0^{\delta_0}\Lambda(\theta,\delta)^p\,\frac{d\delta}{\delta}<\infty,
\]

and asks whether it is sufficient for \(p\ne 2\).

## Background

For \(p=2\), the source cites a theorem giving an if and only if condition in terms of the same cap quantity with exponent \(2\).

## Known Context

- Fourier decay of \(\sigma\) implies \(L^p\)-boundedness for \(1<p\le\infty\), but the goal is a weaker geometric condition.
- Testing on thin strips gives a necessary condition involving the cap length function \(\Lambda(\theta,\delta)\).

## Data Still Needed

- Write the cap definitions \(C^\pm(\theta,\delta)\) and \(\Lambda(\theta,\delta)\) in full.
- Check whether the \(p\ne2\) sufficiency question has been resolved since the source.
