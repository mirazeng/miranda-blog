---
title: Diff approach of In-order traversal
date: 2024-11-01 14:00:27
tags: algorithm, tree
---

## Pseudo-code for approach 1
```
while stack is not empty or current is not null
    if current is not null
        push current to stack
        current = current.left
    else
        current = stack.pop()
        print current
        current = current.right
```
