---
id: problem-006
title: "A convolution inequality on spheres"
primary_category: "调和分析"
secondary_categories:
  - "几何分析"
status: "raw"
created: "2026-07-03"
language: "mixed zh/en"
source:
  title: "Some Problems in Harmonic Analysis"
  url: "https://grafakos.missouri.edu/preprints/Problems6.pdf"
  source_problem_number: 1
  contributor: "Almut Burchard"
keywords:
  - harmonic analysis
  - rearrangement inequalities
  - spherical convolution
  - Riesz-Sobolev inequality
---

# Problem 006 - A Convolution Inequality on Spheres

## Source

This is Problem 1 from "Some Problems in Harmonic Analysis", contributed by Almut Burchard.

## Problem Statement

Let \(u \in S^d \subset \mathbb R^{d+1}\), and let \(\sigma_u\) be reflection across the hyperplane \(u^\perp\). For functions \(f,g\) on \(S^d\), define

\[
(f*g)(u)=\int_{S^d} f(x)g(\sigma_u x)\,dx.
\]

The question is whether the associated rearrangement inequality

\[
\int \Phi(f*g) \le \int \Phi(f^\#*g^\#)
\]

holds for every increasing convex function \(\Phi\) on \(\mathbb R_+\), where \(f^\#\) and \(g^\#\) are symmetric decreasing rearrangements about the north pole.

## Background

The Euclidean Riesz-Sobolev inequality admits strong rearrangement forms. The source asks whether an analogous inequality survives for this reflection-based convolution on spheres.

## Known Context

- The natural group-convolution analogue on \(O(d+1)\) or \(S^d\) is expected to fail.
- The reflection-restricted convolution is open in dimensions \(d>1\).
- The case \(S^1\) is related to a theorem of Baernstein.

## Data Still Needed

- Specify whether the first target is a proof in all dimensions or a concrete low-dimensional test case.
- Record known equality or failure mechanisms for related spherical rearrangement inequalities.
