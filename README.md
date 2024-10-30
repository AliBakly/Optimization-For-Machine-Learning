# Optimization For Machine Learning

This repository contains implementations and analyses of some optimization algorithms, focusing on theoretical guarantees and empirical performance.

## Contents

1. `lasso-optimization.ipynb`
   - Study of the LASSO optimization problem using two methods:
     - FISTA (Fast Iterative Shrinkage-Thresholding Algorithm) with constant stepsize
     - Adaptive Proximal Gradient Method
   - Implementation based on:
     - Beck & Teboulle (2009) "A Fast Iterative Shrinkage-Thresholding Algorithm for Linear Inverse Problems"
     - Malitsky & Mishchenko (2024) "Adaptive Proximal Gradient Method for Convex Optimization"

2. `power-method.ipynb`
   - Implementation of Example 13.11 from Beck (2017)
   - Study of maximization problem with quadratic objective and unit ball constraint
   - Analysis using conditional gradient method (Power Method)
   - Based on Beck (2017) "First-Order Methods in Optimization"

3. `mirror-descent.ipynb`
   - Implementation of Mirror Descent algorithm for minimizing maximum absolute value
   - Study of optimization over unit simplex using Bregman divergence
   - Based on Beck (2017) "First-Order Methods in Optimization"

## Key Features

- Each notebook includes:
  - Theoretical background and problem formulation
  - Detailed implementation with clear comments
  - Visualization of convergence behavior
  - Discussion of results in relation to theoretical guarantees

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- CVXPY (for LASSO optimization)

## Usage

Each notebook is self-contained with following sections:
1. Problem Statement & Background
2. Implementation Details
3. Experimental Results
4. Discussion & Theoretical Connections

## References

- Beck, A. (2017). First-Order Methods in Optimization. Society for Industrial and Applied Mathematics.
- Beck, A., & Teboulle, M. (2009). A Fast Iterative Shrinkage-Thresholding Algorithm for Linear Inverse Problems.
- Malitsky, Y., & Mishchenko, K. (2024). Adaptive Proximal Gradient Method for Convex Optimization.
