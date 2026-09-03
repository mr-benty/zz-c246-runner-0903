---
name: c246-availability-probe
description: Report the environment it runs in
on:
  issues:
    types: [opened]
---

When this workflow runs, report: the operating system name, whether a shell tool is available,
and the absolute path of your working directory. Do nothing else. Do not modify any files.
