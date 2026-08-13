---
id: problem-046
title: "Montanaro--Osborne quantum KKL conjecture"
primary_category: "离散分析、局部理论与量子布尔函数"
secondary_categories: ["quantum Boolean functions", "influences", "KKL conjecture"]
status: "raw"
created: "2026-08-13"
language: "mixed zh/en"
source:
  title: "Supplied PDF transcription"
  locator: "1.4"
  note: "Bibliographic source and status were removed from the supplied transcription."
keywords: ["quantum KKL", "matrix algebra", "variance", "bit-flip derivative"]
---

# Problem 046 - Montanaro--Osborne Quantum KKL Conjecture

Let \(T\in M_2^{\otimes n}\) be a quantum Boolean function: \(T=T^*\) and \(T^*T=1\). Let \(d_j(T)\) be its quantum bit-flip derivative in coordinate \(j\), and write

\[
\operatorname{var}(T)=\operatorname{tr}(|T|^2)-|\operatorname{tr}(T)|^2.
\]

Does a universal \(C>0\) satisfy

\[
\max_{j\in[n]}\|d_j(T)\|_{L^2(M_2^{\otimes n})}^2
\ge C\frac{\operatorname{var}(T)\log n}{n}
\]

for every \(n\) and every such \(T\)?
