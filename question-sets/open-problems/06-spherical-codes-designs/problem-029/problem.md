---
id: problem-029
title: "Covering radius problem for spherical point sets"
primary_category: "球面编码与设计"
secondary_categories:
  - "离散几何与组合"
status: "raw"
created: "2026-07-03"
language: "mixed zh/en"
source:
  title: "G2C2 Lecture No. 1. Spherical t-designs"
  local_file: "G2C2.LectureNo.1(Bannai).pdf"
  lecturer: "Eiichi Bannai"
  date: "2024-08-12"
keywords:
  - covering radius
  - spherical covering
  - spherical codes
  - metric geometry
---

# Problem 029 - Covering Radius Problem for Spherical Point Sets

## Source

This is taken from Eiichi Bannai's G2C2 Lecture No. 1 on spherical \(t\)-designs.

## Problem Statement

For a fixed \(N\), among all \(N\)-point subsets \(X=\{x_1,\ldots,x_N\}\subset S^{n-1}\), minimize

\[
\max_{x\in S^{n-1}}\min_{1\le i\le N} d(x,x_i).
\]

Determine the minimum covering radius and characterize the configurations that attain it.

## Background

The covering radius problem asks for finite point sets that best approximate the whole sphere in the metric sense. It is a design-flavored counterpart to packing and energy problems.

## Known Context

- It is closely related to spherical covering, quantization, and mesh norm problems.
- The lecture presents it as a standard coding-theoretic problem for finite subsets of spheres.

## Data Still Needed

- Choose dimension and metric normalization for first detailed tracking.
- Record known exact values and asymptotic bounds.
