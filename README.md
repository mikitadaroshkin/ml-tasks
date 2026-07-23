# ml-tasks

A small set of self-contained data-science practice notebooks, each solving a standalone problem.

## What this is

Data-science practice notebooks (2019) written in Python with NumPy, SciPy, and matplotlib. Every folder is an independent exercise on a core numerical / machine-learning topic:

- Analysis of text similarity - builds a bag-of-words frequency matrix over a set of sentences and ranks them by cosine distance to find the closest matches.
- Function approximation - approximates a smooth function with a polynomial, solving the resulting linear system for the coefficients using `scipy.linalg`.
- Smooth function optimization - locates minima of a function with a gradient-based method (BFGS) and a global one (differential evolution), and contrasts their behaviour on a smooth versus a non-smooth version.

## License

MIT - see [LICENSE](LICENSE).
