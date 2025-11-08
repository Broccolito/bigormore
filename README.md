# Publish Big or Publish More?

A Mathematical Framework for Deciding Whether to Bundle or Separate Scientific Findings

## Overview

Researchers often face a critical decision: should they bundle multiple related findings into one high-impact paper, or publish them separately as focused, standalone contributions? This project provides a mathematical framework to optimize this decision based on expected utility.

## The Problem

Smaller, tightly scoped papers are easier to read and evaluate, but bundling findings into a "flagship" paper may:
- Present a more coherent narrative
- Capture complete conceptual understanding
- Target higher-impact venues

However, larger papers are harder to write, harder to review, and risk overwhelming readers.

## Mathematical Framework

The framework models each finding as having a value distribution reflecting impact, utility, visibility, and contribution. For *k* findings:

**Strategy A: Publish Separately**
- Optimize each finding independently for its best journal tier
- Total utility: sum of individual optimized utilities

**Strategy B: Bundle into One Paper**
- Optimize the combined value of all findings together
- Target single high-impact venue based on aggregate utility

**Decision Rule:** Compare expected utilities from both strategies and choose the one that maximizes total value.

**Hybrid Strategy:** Bundle core findings into a flagship paper while publishing niche/tail contributions separately.

## Key Insights

- If findings have similar distributional weight, bundling is more viable
- If findings differ significantly in expected impact, separate publication is safer
- Hybrid core-tail strategies emerge naturally as mathematically valid optima
- The utility function is flexible and can incorporate: scientific impact, citations, translational value, public benefit, prestige, time-to-publish, and workload costs

## Theoretical Foundation

Adapted from mechanism design theory for revenue maximization under multiple independent goods (Myerson 1981; Li & Yao 2013).

## Author

Wanjun Gu

## References

- RB Myerson, Optimal auction design. Math Oper Res 6, 58–73 (1981).
- X. Li, A. C.-C. Yao, On revenue maximization for selling multiple independently distributed items. Proc. Natl. Acad. Sci. U. S. A. 110, 11232–11237 (2013).
