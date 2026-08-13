---
id: problem-051
title: "Mendel--Naor heat smoothing"
primary_category: "离散分析、局部理论与量子布尔函数"
secondary_categories: ["discrete cube", "heat semigroup", "Fourier--Walsh analysis"]
status: "raw"
created: "2026-08-13"
language: "mixed zh/en"
source:
  title: "Supplied PDF transcription"
  locator: "1.9"
  note: "Bibliographic source and status were removed from the supplied transcription."
keywords: ["heat smoothing", "tail space", "dimension-free decay"]
---

# Problem 051 - Mendel--Naor Heat Smoothing

On \(\{-1,1\}^n\), let \(W_S(x)=\prod_{i\in S}x_i\), \(\widehat f(S)=\mathbb EfW_S\), and

\[
P_tf=\sum_{S\subseteq[n]}e^{-t|S|}\widehat f(S)W_S.
\]

For every \(1<p<\infty\), does there exist \(c(p)>0\), independent of \(n,k,t,f\), such that if \(\mathbb EfW_S=0\) whenever \(|S|<k\), then

\[
\|P_tf\|_p\le e^{-tkc(p)}\|f\|_p
\qquad(t>0)?
\]
