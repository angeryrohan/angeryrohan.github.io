---
title: Elementwise Fusion Pass for MLIR Linalg
date: 2026-02-10
summary: An MLIR pass that fuses chains of elementwise ops before GPU lowering, cutting kernel launch overhead on a small transformer workload.
metric: -31% kernel launches
tags: MLIR, Linalg, GPU, codegen
link: https://github.com/angeryrohan/your-repo
---

## The problem
Describe the concrete problem in 2-4 sentences. What was slow / broken / missing?
Name the workload and the baseline so the number below means something.

## How I solved it
Walk through the approach. What IR level did you work at? What pass did you write,
what did it match, what did it rewrite it to? Mention the tricky part.

## Result
State the measured outcome and how you measured it (hardware, benchmark, methodology).
A real number beats any adjective here.
