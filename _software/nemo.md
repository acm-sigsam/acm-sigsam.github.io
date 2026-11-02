---
title: Nemo
page_title: Nemo
category: Special Purpose Systems, Packages and Libraries
listed: true
position: 24
summary: a computer algebra package for the Julia programming language.
vendor: null
website: https://nemocas.github.io/Nemo.jl/stable/
previous_website: null
repo: https://github.com/Nemocas/Nemo.jl
link: https://nemocas.github.io/Nemo.jl/stable/
status: active
status_notes: Simplified 2-clause BSD licence for the Julia files (parts MIT; LICENSE.md); version 0.57.0 released 7 October 2026.
link_sources: &id001
- https://nemocas.github.io/Nemo.jl/stable/
- https://github.com/Nemocas/Nemo.jl
- https://raw.githubusercontent.com/Nemocas/Nemo.jl/master/README.md
- https://raw.githubusercontent.com/Nemocas/Nemo.jl/master/CITATION.bib
- https://raw.githubusercontent.com/Nemocas/Nemo.jl/master/LICENSE.md
- https://api.crossref.org/works/10.1145/3087604.3087611
contact: null
citation_note: From the CITATION.bib of the repository (verbatim); DOI checked against Crossref.
citation: |-
  @inproceedings{Nemo.jl-2017,
    author = {Fieker, Claus and Hart, William and Hofmann, Tommy and Johansson, Fredrik},
    title = {Nemo/Hecke: Computer Algebra and Number Theory Packages for the Julia Programming Language},
    booktitle = {Proceedings of the 2017 ACM on International Symposium on Symbolic and Algebraic Computation},
    series = {ISSAC '17},
    year = {2017},
    pages = {157--164},
    numpages = {8},
    url = {https://doi.acm.org/10.1145/3087604.3087611},
    doi = {10.1145/3087604.3087611},
    publisher = {ACM},
    address = {New York, NY, USA},
  }
added: '2026-10-11'
sources: *id001
---

Nemo is a computer algebra package for the Julia programming language that aims to cover commutative algebra, number theory and group theory (README). It wraps the FLINT library (which now contains the former Arb, Antic and Calcium) and re-exports the generic rings and matrix spaces of AbstractAlgebra.jl (README).
