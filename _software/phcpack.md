---
title: PHCpack
page_title: PHCpack
category: Special Purpose Systems, Packages and Libraries
listed: true
position: 38
summary: a software package to solve polynomial systems by homotopy continuation methods.
vendor: null
website: http://homepages.math.uic.edu/~jan/download.html
previous_website: null
repo: https://github.com/janverschelde/PHCpack
link: http://homepages.math.uic.edu/~jan/download.html
status: active
status_notes: GNU GPL version 3; latest release v2.4.94 (16 April 2026) on GitHub.
link_sources: &id001
- http://homepages.math.uic.edu/~jan/download.html
- http://homepages.math.uic.edu/~jan/PHCpack/phcpack.html
- https://github.com/janverschelde/PHCpack
- https://raw.githubusercontent.com/janverschelde/PHCpack/master/README.md
- https://api.github.com/repos/janverschelde/PHCpack/releases?per_page=1
- https://api.crossref.org/works/10.1145/317275.317286
contact: null
citation_note: 'No ''how to cite'' found; built from the Crossref record of J. Verschelde, ''Algorithm 795: PHCpack: a general-purpose solver for polynomial systems by homotopy continuation'', ACM TOMS 25(2), 1999 (doi:10.1145/317275.317286), the paper the README names for version 1.0.'
citation: |-
  @article{Verschelde1999PHCpack,
    author = {Verschelde, Jan},
    title = {Algorithm 795: {PHCpack}: a general-purpose solver for polynomial systems by homotopy continuation},
    journal = {ACM Transactions on Mathematical Software},
    volume = {25},
    number = {2},
    pages = {251--276},
    year = {1999},
    publisher = {Association for Computing Machinery (ACM)},
    doi = {10.1145/317275.317286}
  }
added: '2026-10-11'
sources: *id001
---

PHCpack, by Jan Verschelde, builds a homotopy containing a system with known solutions and tracks the solution paths numerically to the solutions of the given system; it computes positive-dimensional solution sets via a numerical irreducible decomposition, restores quadratic convergence at isolated singularities by deflation, and has interfaces for Python (phcpy), Maple, MATLAB/Octave, SageMath and Macaulay2 (repository README and download page).
