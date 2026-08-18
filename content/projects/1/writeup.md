---
title: Example of a Pass
description: Fuses elementwise ops before GPU lowering to cut launch overhead.
---

title: What actually happens when MLIR lowers a matmul
date: 2026-02-14
summary: Tracing a single matmul from Linalg down to GPU code, one dialect at a time.
tags: MLIR, explainer
---

## Why I wrote this
One or two sentences on what confused you before, and what clicked.

## The lowering, step by step
Explain it the way you'd explain it to yourself six months ago. Use real IR snippets:

```mlir
%0 = linalg.matmul ins(%a, %b : tensor<..>, tensor<..>)
                   outs(%c : tensor<..>) -> tensor<..>
```

Break down each stage. Short sections, concrete examples.

## What I'd still like to understand
Honest open questions signal genuine engagement — hiring managers read this as
someone who reasons about the domain, not someone reciting a tutorial.
