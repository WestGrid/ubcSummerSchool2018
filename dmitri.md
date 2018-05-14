---
layout: default
title: Speeding up Python code with C/C++
nav: false
---

**Instructor**: Dmitri Rozmanov (University of Calgary)

**Title**: Speeding up Python code with C/C++

Python is a popular programming language in the scientific community. A wide variety of available
built-in and external libraries makes it an excellent choice for data analytics and data manipulation
tasks. While Python is an interpretive programming language and quite slow when compared with compiled
computer codes, the library functions are normally implemented in fast compiling languages, such as C or
C++. Using such fast functions as building block for analytical Python programs allows to write fast and
efficient tools for working with your research data. However, what to do when there is no library
function available to do the work you need to perform on your data? Implementing the method in pure
Python may be too slow to be practical.

In this course we will learn a way to create your own custom fast functions and call them from a native
Python code to address such a situation.

**Target audience**: general

**Course plan**:

* Develop an example Python program.
* Measure times required to execute different parts of the program.
* Find the most time-consuming part of the code.
<!-- * Evaluate the time required to run it and project to the production target. -->
* Implement the time-critical part in C++.
* Modify the Python program to take advantage of the compiled C++ function.
* Evaluate the speed-up.

**Duration**: 3 hours

**Level**: beginner to intermediate

**Prerequisites**: Prerequisites: Some familiarity with C++ and Python will be an asset but not required.

**Setup**:
- *Cluster reservation*: 1 core per user
- *Cluster software*: GNU Screen, GCC compiler suite, Python 2.7, GNUPlot
- *Laptop software*: SSH client (built-in on Mac/Linux, on Windows MobaXTerm) for connecting to the
  cluster, optionally an X-windows server (XQuartz on Mac, MobaXTerm on Windows) for plotting
  benchmarking results with GNUPlot

<!-- SciNet has a page on virtualenv -->
<!-- https://wiki.scinet.utoronto.ca/wiki/index.php/User_Python_virtualenv -->
<!-- and talk to Doug -->

<!-- Patrick mentioned phoenix package for C++ from python -->
<!-- - is it this one http://www.boost.org/doc/libs/1_64_0/libs/phoenix/doc/html/phoenix/introduction.html -->
