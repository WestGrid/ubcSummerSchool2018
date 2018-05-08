---
layout: default
title: Introduction to GPU programming with CUDA
nav: false
---

**Instructor**: Dr. Juan Carlos Zuniga-Anaya (University of Saskatchewan)

**Title**: Introduction to GPU programming with CUDA

This is a general introduction to the GP-GPU programming model and the use of CUDA and C to implement
parallel computations in modern NVIDIA-GPU devices. The course also provides a series of examples and
practical exercises where the attendees will be able to implement the concepts and techniques learned.

**Target audience**: anyone interested in learning CUDA from C

**Course plan**:
1. Overview of GPU computing
  - what is a GPU?
  - GPU architecture
  - GPU programming approaches
1. CUDA programming model
  - data parallelism
  - thread hierarchy
  - memory model
1. Synchronicity in CUDA
  - task timeline (kernels, transfers, CPU computations)
  - concurrency
  - streams and events (synchronization)
1. Profiling and optimization of CUDA kernels
  - instrumenting code, and the NVIDIA profiler
  - occupancy (memory latency, stalls)
  - branching, iterations, loops

Note that contents won't be given in strict order, but rather "as needed" during the solution of examples
and exercises, combining presentation of concepts with hands-on experiences.

**Duration**: 6 hours

**Level**: intermediate

**Prerequisites**: Some programming background is required. In particular, basic knowledge of C or C++ is
necessary to follow the examples and exercises.

**Setup**:
- *Cluster reservation*: ideally 1 GPU per student (this way we can fit 4 students per node on Cedar,
  only 2 per node on Graham)
- *Laptop software*: SSH client (built-in on Mac/Linux, on Windows MobaXTerm or PuTTY)
