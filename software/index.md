---
layout: page
title: software
excerpt: "software"
search_omit: false
---

---

# Open source software

### cottoncandy

_Python package for storing arrays on the cloud_

[![GitHub](https://img.shields.io/badge/GitHub-cottoncandy-blue)](https://github.com/gallantlab/cottoncandy)
[![Downloads](https://pepy.tech/badge/cottoncandy)](https://pepy.tech/project/cottoncandy)
[![Build Status](https://github.com/gallantlab/cottoncandy/actions/workflows/run_tests.yml/badge.svg)](https://github.com/gallantlab/cottoncandy/actions/workflows/run_tests.yml)
[https://github.com/gallantlab/cottoncandy](https://github.com/gallantlab/cottoncandy)

`cottoncandy` is a a Python package for storing and accessing numpy array data on S3. This is achieved by reading arrays from memory and downloading arrays directly into memory. This means that you don't have to download your array to disk, and then load it from disk into your python session.

### pymoten

_Computer vision package for extracting motion energy features from videos._

[![GitHub](https://img.shields.io/badge/GitHub-pymoten-blue)](https://github.com/gallantlab/pymoten)
[![Downloads](https://pepy.tech/badge/pymoten)](https://pepy.tech/project/pymoten)
[![coverage](https://codecov.io/gh/gallantlab/pymoten/branch/main/graph/badge.svg)](https://codecov.io/gh/gallantlab/pymoten)
[https://github.com/gallantlab/cottoncandy](https://github.com/gallantlab/cottoncandy)

`pymoten` is a Python package that provides a convenient way to extract motion energy features from video using a pyramid of spatio-temporal Gabor filters. The filters are created at multiple spatial and temporal frequencies, directions of motion, screen positions, and sizes. Each filter quadrature-pair is convolved with the video and their activation energy is computed for each frame. These features provide a good basis to model brain responses to natural movies.

### tikreg

_Machine learning package for Tikhonov, ridge, and banded ridge regression._

[![GitHub](https://img.shields.io/badge/GitHub-tikreg-blue)](https://github.com/gallantlab/tikreg)
[![Downloads](https://pepy.tech/badge/tikreg)](https://pepy.tech/project/tikreg)
[![coverage](https://codecov.io/gh/gallantlab/tikreg/branch/main/graph/badge.svg)](https://codecov.io/gh/gallantlab/tikreg)

`tikreg` is a Python package for Tikhonov regression (a.k.a. L2-regularized regression). Tikhonov regression provides a general framework for estimating encoding models with non-spherical multivariate normal priors. This framework is useful to model biological signals. This package was developed to analyze brain data collected using functional magnetic resonance imaging. tikreg can also be used to model other neuroimaging signals (e.g. 2P, ECoG, etc) and LTI signals more generally.

See latest implementation in: [https://github.com/gallantlab/himalaya](https://github.com/gallantlab/himalaya/)

### fusilib

_Signal processing package for functional ultrasound and electrophysiology data_
[https://github.com/anwarnunez/fusi](https://github.com/anwarnunez/fusi)

<!-- [![GitHub](https://img.shields.io/badge/GitHub-fusilib-blue)] -->

Implements temporal, frequncy and spatial domain analyses related to [Nunez-Elizalde, et al., 2022](https://doi.org/10.1016/j.neuron.2022.02.012).
