---
id: problem-038
title: "Classification of entire planar Ginzburg-Landau vortices"
primary_category: "Ginzburg-Landau 方程"
secondary_categories:
  - "整平面解"
  - "涡旋分类"
status: "active"
created: "2026-08-06"
language: "mixed zh/en"
source:
  title: "Some of My Favorite Open Problems"
  author: "Haim Brezis"
  locator: "Open Problem 2.4"
  url: "https://ems.press/journals/rlm/articles/13272471"
keywords:
  - entire Ginzburg-Landau equation
  - vortex classification
  - finite potential energy
  - degree at infinity
  - equivariant solutions
---

# Problem 038 - Classification of Entire Planar Ginzburg-Landau Vortices

## Source

This is Brezis Open Problem 2.4 from "Some of My Favorite Open Problems".

## Problem Statement

Let \(u:\mathbb R^2\to\mathbb R^2\simeq\mathbb C\) be a smooth solution of

\[
-\Delta u=u(1-|u|^2)
\qquad\text{in }\mathbb R^2
\]

such that

\[
|u(x)|\to1
\qquad\text{as } |x|\to\infty.
\]

Let \(q=\deg(u,\infty)\in\mathbb Z\). For each \(q\), the standard equivariant vortex is

\[
V_q(r,\theta)=e^{iq\theta}g_q(r),
\]

where

\[
\begin{cases}
-g_q''-\dfrac1r g_q'+\dfrac{q^2}{r^2}g_q
=g_q(1-g_q^2),\\
g_q(0)=0,\qquad g_q(r)\to1\quad(r\to\infty).
\end{cases}
\]

Must every such entire solution satisfy

\[
u(x)=\alpha V_q(x-x_0)
\]

for some \(x_0\in\mathbb R^2\) and \(\alpha\in\mathbb C\), \(|\alpha|=1\)?

## Current Mathematical Boundary

- The classification is complete for \(q=0\) and \(q=\pm1\) after combining older finite-potential-energy classification theorems with the 2026 finite-potential-energy breakthrough.
- The case \(|q|\ge2\) remains open.
- Proposed nonradial multi-vortex constructions for \(|q|\ge2\) have not become accepted complete counterexamples.

## Recent Breakthrough

Chen, Wei, Yan, and Yang proved in 2026 that every smooth entire solution with \(|u(x)|\to1\) has finite potential energy:

\[
\int_{\mathbb R^2}(1-|u|^2)^2\,dx<\infty.
\]

This resolves Brezis Open Problem 2.5 and removes the extra finite-potential-energy assumption in the known \(q=0,\pm1\) classifications.

## Data Still Needed

- Track the status of the 2026 preprint through peer review.
- Separate the low-degree classification, now settled modulo the 2026 preprint, from the high-degree \(|q|\ge2\) problem.
- Reassess possible nonradial multi-vortex constructions for \(|q|\ge2\).
