# AI MSc

Degree repository. Each semester is a submodule under `semesters/`. Each semester in turn holds its courses as submodules.

## Semesters

| Semester | Path | Repository |
|---|---|---|
| Fall 2026 | [semesters/MSc_Fall_2026](semesters/MSc_Fall_2026) | [AliNikkhah2001/MSc_Fall_2026](https://github.com/AliNikkhah2001/MSc_Fall_2026) |

Fall 2026 currently contains Deep Generative Models (`DGM_25855`), including Homework 1 and Homework 2.

## Clone

```bash
git clone --recurse-submodules https://github.com/AliNikkhah2001/AI_MSc.git
```

That fetches the degree, the semester, and the course. If a checkout is missing a nested repository:

```bash
git submodule update --init --recursive
```
