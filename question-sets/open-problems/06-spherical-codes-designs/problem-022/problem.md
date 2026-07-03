---
id: problem-022
title: "Tammes problem for spherical point configurations"
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
  - Tammes problem
  - spherical codes
  - minimum distance
  - contact graphs
---

# Problem 022 - Tammes Problem for Spherical Point Configurations

## Source

This is taken from Eiichi Bannai's G2C2 Lecture No. 1 on spherical \(t\)-designs.

## Problem Statement

For a fixed integer \(N\), determine the configuration \(X\subset S^{n-1}\) with \(|X|=N\) that maximizes the minimum Euclidean distance

\[
d(X)=\min\{ \|x-y\| : x,y\in X,\ x\ne y\}.
\]

In the classical three-dimensional Tammes problem, this asks for the best placement of \(N\) points on the unit sphere \(S^2\).

## Background

The lecture lists Tammes-type problems as a coding-theoretic viewpoint on finite subsets of spheres: points should be as separated as possible.

## Known Context

- Several values of \(N\) on \(S^2\) are classically solved.
- The lecture notes highlight solved cases through \(N=14\) and \(N=24\), with computer-assisted contact graph methods appearing in modern solutions.

## Data Still Needed

- Decide whether this repository entry tracks the general \(S^{n-1}\) problem or the classical \(S^2\) problem first.
- Build a solved/open table by \(N\) and dimension.
