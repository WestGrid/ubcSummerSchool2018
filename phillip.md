---
layout: default
title: Next Generation Sequencing on Cedar
nav: false
---

**Instructor**: Phillip Richmond (UBC)

**Title**: Next Generation Sequencing Read Mapping and Visualization: A common part of analysis for
diverse data types.

Processing bioinformatics data on Cedar.

**Target audience**: bioinformaticians

**Course plan**:

* 9-9:30 (Lecture) - Into to Short read mapping and different data types: ChIP-seq (TF, H3K27?), DNA-seq,
  GRO-seq (if there is time)
* 9:30-10:15 (Follow-along) - Read mapping of different data files using salloc (BWAmem, samtools) and SLURM
* 10:15-10:45 (Independent) - Coffee & Problem Set 1 (Choose files from directory, make edits to scripts
  so they work, map and convert to bam)
* 10:45-11:15 (Follow-along) - Download processed data from Cedar to local machine (OR Mount Cedar** Something to discuss)
* 11:15-11:30 (Lecture) - Next steps you could take with this data, including pointing to job scripts
  that can handle peak calling (bedtools —> HOMER) or variant calling (Picard —> GATK)
* 11:30-12:00 (Independent) - Problem set 2 (Play with some of the other downstream processing steps on
  the data you started with)

**Duration**: 3 hours

**Level**: beginner?

**Prerequisites**: familiarity with Linux and [*Introduction to HPC*]({{ site.baseurl }}/roman.html) (Day
1) course

**Setup**: Cedar reservation?

<!-- - ask if Philip covers snakemake; if not, Jamie could look into teaching it using hpc-python materials -->
