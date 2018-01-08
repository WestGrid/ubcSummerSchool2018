This section will be delivered in three parts by three separate instructors, in the order listed below.

**Duration**: 3 hours

### Part 1: Designing and running a high-throughput production alignment and base calling pipeline

**Instructor**: Eric Chuah (BC Cancer Agency)

**Course description**: This course will give a brief overview of the high throughput sequencing platform
at Canada’s Michael Smith Genome Sciences Centre (BCGSC) and a description of the base calling and
alignment pipeline that is used to process the raw sequence data generated.

The topics covered will include the network, file system and cluster infrastructure that is in place to
support processing the large amounts of data that is generated as well as archiving and compression of
the resulting files from the analyses (FASTQs and BAMs).  The base calling and alignment pipelines will
include how we handle multiplexed samples, read trimming, genomic references based on taxonomy, sample
type and sample priority.

Additional considerations are the different types of failures in analyses that may occur and how to
handle them, monitoring turnaround times and incremental improvements to the pipelines using a
data-driven approach.

**Instructor bio**: Eric Chuah is a LIMS Bioinformatics Coordinator at the BC Cancer Agency. He started
at the agency in 2004 and now manages a team of developers who focus on developing web interfaces for
laboratory sample tracking, analysis automation, data submission and APIs for downstream bioinformatics
teams. He has a keen interest in databases and visualization. He studied at Simon Fraser University and
BCIT.

**Level**: beginner

**Prerequisites**: None

### Part 2: Approaches to Quality Control of Next Generation Sequencing data

**Instructor**: Kane Tse (BC Cancer Agency)

**Course description**: Canada's Michael Smith Genome Sciences Centre (BCGSC) a fleet of Illumina next
generation sequencers. A single instrument is capable of generating up to 6.5 TB (terabytes) or 600
million read sequences of data every 3 days, or an equivalent of over 100 lanes per week. Quality
Control is critical to ensure that error-free data is delivered in a timely manner to collaborators and
researchers around the world. Using an HPC cluster, the Bioinformatics Quality Control team (BioQC) has
developed a software pipeline to processes every read from every lane to provide a clear picture of the
quality of a library.

In this course, you will be introduced to basic concepts of how to identify bottlenecks; determining
resource usage and constraints; and how to optimize job size versus number to ensure that a parallel
cluster environment is carefully managed to ensure that data is processed efficiently and effectively.

**Instructor bio**: Kane Tse is an Assistant Bioinformatic Coordinator at the BC Cancer Agency. He has
worked in both the public and private sectors working on scientific and pharmaceutical research projects
in Silicon Valley and Canada. He moved to Vancouver in 2003 to work for a Biotechnology start-up company
and now performs both pipeline software development as well as data analysis. He is a certified Oracle
Database Administrator and manages the Quality Control group at the Genome Sciences Centre. He studied
at the University of Calgary and Stanford University.

**Level**: intermediate

**Prerequisites**: Basic knowledge of Next-Generation Sequencing principles

### Part 3: Considerations for Bioinformatic Analysis Workflow Design & Development

**Instructor**: Nina Thiessen (BC Cancer Agency)

**Course description**: This course will give an overview of the fundamental principles used by the
production bioinformatics group at Canada's Michael Smith Genome Sciences Centre (BCGSC) to guide the
design and development of high-throughput NGS analysis workflows that can produce world-class results
suitable for publication.

The design and development considerations discussed in this course will focus on the needs of a
high-throughput semi-automated environment and will include topics such as: file management when dealing
with very large files, ensuring analysis robustness, validating correctness, defining quality control
gates, options for analysis tracking, writing good documentation, and avoiding common pitfalls.

**Instructor bio**: Nina Thiessen is a Bioinformatics Coordinator at the BC Cancer Agency. She has a
decade of experience managing a team of Computational Biologists who design and develop genome and
transcriptome analysis workflows, providing tailor-made support for individual projects as well as
support for core production needs. She has overseen analysis for many high-profile international
collaborations which have resulted in numerous publications in top-tier journals. She studied Computer
Science at the University of Manitoba and obtained a Master's degree from the University of Toronto as a
member of the Machine Learning Group.

**Level**: beginner

**Prerequisites**: None
