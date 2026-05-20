# Portfolio Optimization with Frank-Wolfe Variants

Academic project developed for the Optimization for Data Science course at the University of Padova.
The project studies constrained mean-variance portfolio optimization using first-order optimization methods, with a particular focus on projection-free algorithms such as Frank-Wolfe and its variants.
Different algorithms were compared on real financial datasets to evaluate convergence behavior, computational efficiency, and sparsity of the resulting portfolio allocations.

## Algorithms

The following methods were analyzed and compared:
- Projected Gradient Descent (PGD)
- Frank-Wolfe (FW)
- Away-Step Frank-Wolfe (AFW)
- Pairwise Frank-Wolfe (PFW)

Both exact line search and diminishing step-size strategies were tested.

## Datasets
Experiments were conducted on real-world market datasets:

- FTSE100
- EUROSTOXX50
- DOWJONES
- S&P500
- NASDAQ100

The analysis includes both low-dimensional and highly ill-conditioned optimization problems.

## Main Findings

Some of the main results obtained during the analysis:

- AFW and PFW achieved the fastest convergence
- Projection-free methods consistently outperformed PGD
- Ill-conditioned datasets highlighted stronger differences between algorithms
- FW variants produced sparser portfolio allocations
- PGD required significantly more iterations and computational time

## Topics Covered

- Convex Optimization
- Portfolio Optimization
- First-Order Methods
- Frank-Wolfe Algorithms
- Projection-Free Optimization
- Numerical Optimization
- Sparse Optimization
