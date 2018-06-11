---
layout: default
title: Next-Gen Sequencing on Cedar
nav: false
---

**Instructor**: Phillip Richmond (UBC)

**Title**: Next-Gen Sequencing Read Mapping and Visualization: A common part of analysis for diverse data types

Processing bioinformatics data on Cedar.

The course slides are [here](https://docs.google.com/presentation/d/1O2BewoJgp-m3aEKYm8XnVlPJBEnBaWeO_UJ0yKhz8Lw).

**Target audience**: bioinformaticians

**Course plan**:

* 9-9:30 (Lecture) - Into to Short read mapping and different data types: ChIP-seq (TF, H3K27?), DNA-seq,
  (GRO-seq)*
* 9:30-10:15 (Follow-along) - Read mapping of different data files using salloc (BWAmem, samtools) and SLURM
* 10:15-10:45 (Independent) - Coffee & Problem Set 1 (Choose files from directory, make edits to scripts
  so they work, map and convert to bam)
* 10:45-11:15 (Follow-along) - Download processed data from Cedar to local machine (OR Mount Cedar**
  Something to discuss)
* 11:15-11:30 (Lecture) - Next steps you could take with this data, including pointing to job scripts
  that can handle peak calling (bedtools —> HOMER) or variant calling (Picard —> GATK)
* 11:30-12:00 (Independent) - Problem set 2 (Play with some of the other downstream processing steps on
  the data you started with)

**Duration**: 3 hours

**Level**: beginner / intermediate

**Prerequisites**: Experience in Linux command line and HPC clusters with SLURM scheduler (covered in
[*Introduction to HPC*]({{ site.baseurl }}/roman.html) course on Day 1). We will provide a short quiz to
measure prerequisites.

**Setup**:
- *Cluster reservation*: 4-8 cores/user.
- *Cluster space*: It would be nice to have 1Tb of disk space where I can deposit toy (subsetted) and
  real datasets that I am going to download from the sequence read archive (SRA). I also need a space to
  store genome data and indexes.
- *Cluster software*: BWA, samtools, GATK, htslib, bedtools, Picard, homer (homer is not installed
  currently, but if you give me a central location on Cedar for this analysis course then I can install
  it http://homer.ucsd.edu/homer/introduction/install.html).
- *Laptop software*: SSH client (built-in on Mac/Linux, on Windows MobaXTerm or PuTTY), IGV, and a way to
  mount Cedar from local machine. I personally use sshfs and OSX Fuse and it works seamlessly, don't know
  what's best for PCs. If we don't mount, then another alternative is to download data onto local machine
  via file transfer (either a client like FileZilla or just command-line scp).
