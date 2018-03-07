---
layout: default
title: Program
nav: true
---

# 2018 notes

- Monday June-11 to Thursday June-14
- website http://bit.ly/ubcwg18
- repo https://github.com/WestGrid/ubcSummerSchool2018.git
- announcement and registration opening around May-01

## What we would like to do differently this year

1. have as much participation from analysts and the UBC ARC staff (teaching the courses)
1. have more stringent rules for faculty-delivered courses: must have hands-ons, must use our national
   systems, must send us a syllabus before a deadline; the same should apply to any GSC presentations so
   that they don’t end up promoting their own clusters
1. find a way to clearly recognize and promote faculty who support the schools / present sessions
1. have a 1h panel on career options after PhD (have HPC background, now what?), bring in people from
   different domains, put this into the program, re-use one of the lecture halls off-schedule, advertsie
   as a networking event, maybe some instructors will want to participate as well

## Action items

**Alex:**
* (with Jana) in the evenbrite registration form have checkboxes for individual courses, so that we know
  the attendance better, maybe set a larger cap this year (20% more attendees?)
* eventual email to faculty: our conditions (also put these on the website)
* email analysts (and then selected CC instructors): we need CUDA (and/or OpenACC) and Julia instructors
* email HPC Intro materials to Roman
* ping Wolfgang Richter and Ata Roudgar again
* talk to Garth: we would much prefer to capture screens with a camera, logistically we don't want to
  support instructor laptops, they might refuse to instal software, etc.
* email Mathworks
  - we are really interested in using the TAH UBC license
  - work with the instructors: need intro, need to show running/scaling on Cedar
  - let them decide on 3h vs 6h
- send to Garth the room numbers as soon as we have them

**Jamie:**
* (with Steve) look into the process to let UBC faculty claim courses to their credit
* talk to Philip Richmond
  - ask if Philip covers snakemake; if not, Jamie could look into teaching it using hpc-python materials
* talk to Martin K from the GSC
* talk to ECOSCOPE folks
* ask at Feb-07 CC bioinformatics meeting for volunteers to teach Galaxy/GenAP

**Roman:**
* ask people about the career panel
* approach Brent about a cloud course
  - if not, ask Ryan Enge
  - if not, ask Venkat (Brent's replacement)
* ask Phil Austin if he wants to repeat his HPC Python course (Parallelization in Python 3 and large datasets)
* talk to Matt from IBM about repeating his Spark/Hadoop course (Data Science at Scale with Hadoop, Spark
  and The Data Science Experience)

**Kamil:**
- room booking (aiming to have the same rooms, still looking)

**someone:**
* do we invite Patrick Walls? (Jupyter notebooks and scientific computing in Python)
* do we invite Schuyler Lindberg? (Introduction to Harvesting API Data in Python from UBC Library's Open Collections)

## Courses

| date and time | lecture theatre | smaller classroom |
| ------------- | --------------- | ----------------- |
| Mon **11th** morning | *Introduction to HPC* by Roman Baranowski | *bioinformatics pipeline on Cedar* by Philip Richmond |
| Mon **11th** afternoon | *Introduction to HPC* by Roman Baranowski (cont.) | |
| Tue **12th** morning | *Chapel* by Alex Razoumov | |
| Tue **12th** afternoon | *Chapel* by Alex Razoumov (cont.) | |
| Wed **13th** morning | *Basics of scientific visualization with ParaView* by Alex Razoumov | Martin Krzywinski (GSC) |
| Wed **13th** afternoon | *Large-scale remote ParaView visualization* by Alex Razoumov | |
| Thu **14th** morning | Phil Austin? | cloud course? |
| Thu **14th** afternoon | Matt McInnis? | *bioinfo and data graphics in R for microbiologists* by ECOSCOPE |

Wolfgang Richter (tentative), or Ata Roudgar (more experienced with installation than using SQL)
- a database workshop
  - 2017-Oct-27: Wolfgang wants to teach a database course in Vancouver but he might not be able due to
    health issues
  - Feb-09: aiming to have the latest MySQL and Postgres service on Cedar by the end of February

## Next face-to-face March-20 @2pm

- discuss the program table
- looking for instructors for the missing pieces
- faculty-contributed courses
  - rules for the faculty
  - how do we clearly recognize and promote faculty who support the schools / present sessions
- recording / broadcasting

## Recording and broadcasting

Garth Feb-27
- would much prefer to use screen-capture software
- either he will travel to Vancouver, or find someone from audio/video support at UBC

## MATLAB

WestGrid would like the courses:
- with lots of hands-on exercises for all attendees (not just demos on the screen), and
- showing how you can scale the workflow to bigger problems on a Compute Canada national cluster (Cedar
    or Graham), and
- ideally with a persistent environment for MATLAB use, including beyond the particular summer courses

We are looking to have a MATLAB session in one of the last two days of the schools. The class could be
either half-day (3 hours) or full-day (6 hours).

Mathworks can easily provide training with the first two requirements met, assuming that
- all the right software is in place for use
- enough lead time to prepare

License types we could use:
1. anyone can install a 30-day self-serve trial of MATLAB from MathWorks website; these licenses don’t
   come with MATLAB Distributed Computing Server; MathWorks could give us access to that on their central
   resource
1. short-course licenses for short courses; this approach will be formalized in the near future but it's
   not yet advertised; can offer access to MATLAB beyond the term of the course
1. use existing access to MATLAB, for the duration of the course and beyond, depending on the course
   attendees’ affiliations

Many schools in Canada have significant MATLAB access, and multiple licenses include MATLAB Distributed
Computing Server access, depending on the site.

- TAH (Total Academic Headcount) / enterprise licenses: allow any student, faculty, or other users of the
  university licenses to use MATLAB and multiple other products
  - UBC has a TAH license with 53 products on it (as of December), all of which accessible by all UBC users
  - with this license, UBC may grant "3rd-party access" to others not at the university, up to
    indefinitely, at their option
- CC and bring-your-own-license (BYOL): CC has a "Hosting Provider" status to enable usage of
  hardware/software resources across universities (users from different universities can use each other's
  hardware/software; however, they must have a local license (at their own site) for the software they
  wish to use on the other university's site

In any case, Mathworks would like to work with us to figure out how to provide training and software
access for the training. If there are reasons why ongoing usage outside the course is a barrier,
Mathworks would like to learn and understand more about that.

Mathworks: as a next step, would it make sense to have a call to work through some of this, maybe get
more of the specific detail and figure out how we can make a training work in a way that meets your
objectives?

Mathworks would be interested to hear more about the backgrounds and disciplines of the attendees so that
we could focus the content appropriately.

In any case, I’ll wait to hear from you. Then we can discuss both topics 1) Providing software access, 2)
training specifics

## Other possible topics

- something on DH on CC hardware
  - tap Even Thornberry, the new GIS librarian at UBC
- HPC Python on CC hardware
- Jupyter notebooks (on CC instances) and scientific computing in Python
- Julia language
- hybrid programming with MPI+OpenMP
- GPU programming with CUDA and/or OpenACC
- CC cloud
- Hadoop, Spark, data science
- OpenMP, MPI (probably not since we'll have Chapel)

&nbsp;

# Last year's program

| date and time | lecture theatre | smaller classroom |
| ------------- | --------------- | ----------------- |
| Monday **June-19** morning | [*Introduction to HPC*](intro.md) by Alex Razoumov ![beginner](images/beginner.png) | [*Bioinformatics session*](bioinfo.md) by Eric Chuah, Kane Tse, Nina Thiessen ![beginner](images/beginner.png) ![intermediate](images/intermediate.png) |
| Monday **June-19** afternoon | [*Introduction to parallel and distributed computing in high-level programming languages (MATLAB and Julia)*](henryk.md) by Henryk Modzelewski and Keegan Lensink ![beginner](images/beginner.png) | [*Introduction to hybrid programming with MPI+OpenMP*](mauricio.md) by Mauricio Ponga ![expert](images/expert.png) |
| Tuesday **June-20** morning | [*Introduction to GPU programming with CUDA and OpenACC*](maxime.md) by Maxime Boissonneault ![intermediate](images/intermediate.png) | [*Introduction to Jupyter notebooks and scientific computing in Python*](patrick.md) by Patrick Walls ![beginner](images/beginner.png) |
| Tuesday **June-20** afternoon | [*Introduction to GPU programming with CUDA and OpenACC*](maxime.md) by Maxime Boissonneault (continued) ![intermediate](images/intermediate.png) | [*Introduction to Harvesting API Data in Python from UBC Library's Open Collections*](schuyler.md) by Schuyler Lindberg ![beginner](images/beginner.png) |
| Wednesday **June-21** morning | [*Introduction to commercial cloud*](scalar.md) by Scalar and Cycle Computing | [*Scientific visualization with ParaView*](visualization.md) by Alex Razoumov ![beginner](images/beginner.png) |
| Wednesday **June-21** afternoon | [*Introduction to Compute Canada Cloud*](brent.md) by Brent Gawryliuk ![beginner](images/beginner.png) | [*Computational Chemistry with Gaussian*](gino.md) by Gino DiLabio ![intermediate](images/intermediate.png) |
| Thursday **June-22** morning | [*Parallelization in Python 3 and large datasets*](https://github.com/phaustin/parallel_python_course/blob/master/austin.md) by Phil Austin ![intermediate](images/intermediate.png) | |
| Thursday **June-22** afternoon | [*Data Science at Scale with Hadoop, Spark and The Data Science Experience*](ibm.md) by Matt McInnis ![beginner](images/beginner.png) | [*Physics and astrophysics modeling*](jeremy.md) by Jeremy Heyl ![intermediate](images/intermediate.png) |
