---
title: Makefile
parent: Tools
nav_order: 1
---

# Makefile related
## Basic structure
  * **Variables:** Store values you can reuse.
  * **Targets:** Named actions you can run.
  * **Dependencies:** Files or targets that must be up-to-date before running a target.
  * **Recipes:** The shell commands to run for each target.

When doing make, there are 2 layers of interpretor,
 1. Layer 1 -- make: ite reads Makefile and expand veriables, rules, dependencies.
 2. Layer 2 -- shell: actrual excution.
