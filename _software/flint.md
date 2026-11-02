---
title: FLINT
page_title: FLINT
category: Special Purpose Systems, Packages and Libraries
listed: true
position: 22
summary: a C library for doing number theory, freely available under the GNU Lesser General Public License version 3 or later.
vendor: null
website: https://flintlib.org/
previous_website: null
repo: https://github.com/flintlib/flint
link: https://flintlib.org/
status: active
status_notes: LGPL version 3 or later; version 3.6.0 (released 29 June 2026).
link_sources: &id001
- https://flintlib.org/
- https://flintlib.org/citation.html
- https://github.com/flintlib/flint
contact: null
citation_note: From the 'Citing FLINT' page of the website (recommended form for version 3.6.0); the page also suggests citing Johansson's Arb paper (IEEE Trans. Computers 66(8), 2017, doi:10.1109/TC.2017.2690633) for the ball-arithmetic component.
citation: |-
  @manual{flint,
    key = {{FLINT}},
    author = {The {FLINT} team},
    title = {{FLINT}: {F}ast {L}ibrary for {N}umber {T}heory},
    year = {2026},
    note = {Version 3.6.0, \url{https://flintlib.org}}
  }
added: '2026-10-11'
sources: *id001
---

FLINT (Fast Library for Number Theory) provides arithmetic in the integers, rationals, algebraic, real, complex and p-adic numbers, finite fields and number fields, together with polynomials, power series and matrices, and is used as a back end by systems such as SageMath, OSCAR, Singular, Macaulay2, Maple and Mathematica (homepage). Since FLINT 3.0 it includes ball arithmetic for real and complex numbers and exact real and complex numbers, from merging the former standalone libraries Arb, Antic and Calcium (homepage).
