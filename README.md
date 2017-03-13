# RLEVectors

`RLEVectors` is an alternate implementation of the Rle type from
Bioconductor's IRanges package by H. Pages, P. Aboyoun and
M. Lawrence. RLEVectors represent a vector with repeated values as the
ordered set of values and repeat extents. In the field of genomics,
data of various types are  measured across the ~3 billion letters in
the human genome can often be represented in a few thousand runs. It
is useful to know the bounds of genome regions covered by these runs,
the values associated with these runs, and to be able to perform
various mathematical operations on these values.

[![0.5](http://pkg.julialang.org/badges/RLEVectors_0.5.svg)](http://pkg.julialang.org/?pkg=RLEVectors)
[![0.6](http://pkg.julialang.org/badges/RLEVectors_0.6.svg)](http://pkg.julialang.org/?pkg=RLEVectors)

[![Build Status](https://travis-ci.org/phaverty/RLEVectors.jl.svg?branch=master)](https://travis-ci.org/phaverty/RLEVectors.jl)
[![Coverage Status](https://codecov.io/github/phaverty/RLEVectors.jl/coverage.svg?branch=master)](https://codecov.io/github/phaverty/RLEVectors.jl?branch=master)

[![](https://img.shields.io/badge/docs-latest-blue.svg)](https://phaverty.github.io/RLEVectors.jl/latest)
[![](https://img.shields.io/badge/docs-stable-blue.svg)](https://phaverty.github.io/RLEVectors.jl/stable)
