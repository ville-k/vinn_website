---
layout: page
title: About
permalink: /about/
---

ViNN is a cross platform MIT-licensed C++ library for training and evaluating artificial neural networks using OpenCL. ViNN parallelizes computationally intensive linear algebra routines using OpenCL providing significant performance gains over a single threaded CPU based implementation. Python bindings with NumPy integration ease developing new models and enable interoperability with existing tools and libraries.

The design goals for ViNN are:

* correctness - use gradient checking, static analysis and strive for 100% unit test coverage
* modularity - for easy integration, extensibility and testing
* performance - optimize performance critical parts using OpenCL
