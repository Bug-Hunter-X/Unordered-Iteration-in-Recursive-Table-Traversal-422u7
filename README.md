# Lua Recursive Table Traversal Bug

This repository demonstrates a potential issue with recursive table traversal in Lua when using the `pairs` iterator.  The `pairs` function doesn't guarantee any specific order of iteration, and this can lead to unexpected results, particularly when the table is modified during traversal. 

The `bug.lua` file contains code that showcases this issue. The `bugSolution.lua` demonstrates how to fix it by using a different traversal strategy.