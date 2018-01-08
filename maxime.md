**Instructor**: Maxime Boissonneault (Calcul Quebec)

**Title**: Introduction to GPU programming with CUDA and OpenACC

**Duration**: full day

**Target audience**: Researchers who develop their own code and consider porting them to GPU

**Level**: intermediate

**Prerequisites**:
* Being able to login and interact (edit files, navigate directories) with a Linux computer in a
  command-line environment using SSH
* Basic understanding of the C (or C++)* language, including pointers and memory allocation
* While both CUDA and OpenACC can be used in Fortran as well as C or C++, not all examples used are
  available in Fortran.

**Course plan**:
1. Understanding the architecture of a GPU and identifying whether an algorithm is a good candidate for
   running on a GPU
1. GPU Programming with CUDA
  1. Understanding the workflow of a CUDA program, writing and compiling a minimal CUDA code and
     compiling CUDA examples
  1. Using CUDA threads and blocks to write parallel algorithms
  1. Optional topics (depending on audience and time)
    1. Using multiple GPUs
	1. Using unified memory in Cuda 6
	1. Asynchronous operations with Cuda streams
1. GPU Programming with OpenACC
    3.1 Profiling existing code and gathering compiler information
    3.2 Expressing parallelism with OpenACC directives
    3.3 Expressing data movement
    3.4 Optimizing loops
