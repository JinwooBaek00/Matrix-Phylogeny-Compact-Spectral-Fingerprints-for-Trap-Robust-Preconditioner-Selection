# Matrix Phylogeny

Compact Chebyshev spectral fingerprints (CSF/ASF) for matrix retrieval and preconditioner recommendation — matrix–vector (matvec) only, eigendecomposition-free.

## Features
- **CSF / ASF**: fixed-K and adaptive-K Chebyshev trace-moment fingerprints (K ≤ 10)
- **Invariant** to similarity, permutation, and global scaling; **noise-stable**
- **Hutchinson** trace sketches; works with sparse / operator-only matrices
- **Probe-and-Switch** policy for trap-robust preconditioner selection

Runs as a single notebook.
Tested on Python 3.11.
