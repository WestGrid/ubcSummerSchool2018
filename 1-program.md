---
layout: default
title: Program
nav: true
---

# 2018 notes

- Monday June-11 to Thursday June-14
- website **http://bit.ly/ubcwg18**
- repository https://github.com/WestGrid/ubcSummerSchool2018.git
- announcement and registration opening around May-01
- rooms GEOG 101 (60 seats), GEOG 147 (60 seats), GEOG 200 (100 seats)

## Courses (tentative program)

- <sup>fixed</sup> means the instructor is available only on this date/time (cannot be moved)

| date and time | lecture theatre | smaller classroom |
| ------------- | --------------- | ----------------- |
| Mon **11th** morning | [*Introduction to HPC*]({{ site.baseurl }}/roman.html) by Roman Baranowski | *Bioinformatics pipeline on Cedar* by Phillip Richmond |
| Mon **11th** afternoon | [*Introduction to HPC*]({{ site.baseurl }}/roman.html) by Roman Baranowski (cont.) | [*Databases*]({{ site.baseurl }}/wolfgang.html) by Wolfgang Richter |
| Tue **12th** morning | [*Parallel programming in Chapel*]({{ site.baseurl }}/alex1.html) by Alex Razoumov | [*Introduction to GPU programming with CUDA*]({{ site.baseurl }}/juan.html) by Juan Zuniga |
| Tue **12th** afternoon | [*Parallel programming in Chapel*]({{ site.baseurl }}/alex1.html) by Alex Razoumov (cont.) | [*Introduction to GPU programming with CUDA*]({{ site.baseurl }}/juan.html) by Juan Zuniga (cont.) |
| Wed **13th** morning | [*Basics of scientific visualization with ParaView*]({{ site.baseurl }}/alex2.html) by Alex Razoumov | [*MATLAB*]({{ site.baseurl }}/mathworks.html) by Mathworks <sup>fixed</sup> |
| Wed **13th** afternoon | [*Large-scale remote visualization with ParaView*]({{ site.baseurl}}/alex3.html) by Alex Razoumov | [*MATLAB*]({{ site.baseurl }}/mathworks.html) by Mathworks (cont.) <sup>fixed</sup> |
| Thu **14th** morning | *Parallelization in Python 3 and large datasets* by Phil Austin <sup>fixed</sup> | *CC cloud* |
| Thu **14th** afternoon | *Amazon AWS* | *Bioinfo and data graphics in R for microbiologists* by ECOSCOPE <sup>fixed</sup> |
{:.mbtablestyle}

| Thu **14th** 4pm-5pm | open panel on post-PhD career options |
{:.mbtablestyle}

&nbsp;

**Notes**:
- removed Martin Krzywinski (GSC) to free the spot for Juan's GPU course, might put him back to replace
  alex2.md; Martin Krzywinski is unsure, has until March to think it over (but not the design course)
- need to find a spot for Dmitri Rozmanov (tentative topic: optimizing Python functions in C++)
- Matt McInnis from IBM is unreachable; Roman is working with other IBM contacts
- Steve Cundy met with Amazon AWS, they really want to participate in our summer school
- CC cloud: Brent interested, needs more time to think, if not then Venkat
- so far no one to teach Julia language

## Next face-to-face Apr-03 @2pm

- fitting Dmitri into the program
- the big room can fit only 100 people
- Cedar reservations: how many nodes? GPU nodes? figure out the grid for the week
- guest accounts
- recording / broadcasting

## Action items

**Alex:**
* talk to Garth
  - we would much prefer to capture screens with a camera, logistically we don't want to support
    instructor laptops, they might refuse to install software, etc.
  - share the room numbers as soon as we have them
* work with Mathworks
  - we are really interested in using the TAH UBC license
  - work with the instructors: need intro, need to show running/scaling on Cedar, make sure everyone can
    access MATLAB
  - full-day
* eventual email to faculty: our conditions (also put these on the website)

**Jamie:**
* Martin Krzywinski has to decide until the end of March
* ECOSCOPE "most likely confirmed" as of Mar-20 (the instructor should fly back into Vancouver on Tuesday)
* Feb-07 CC bioinformatics meeting: volunteers to teach Galaxy/GenAP?

**Roman:**
* Mar-20 has not head back from Gino DiLabio
* Mar-20 has not head back from Ian Allison (PIMS) on someone from his team to teach Jupyter/Python; Ian
  himself will be in Europe; could be Patrick Walls?
* Mar-20 contacting people about participating in the career panel (Brent, finance, etc)

**Kamil:**
- room booking: 2017 Pharmacy rooms not available, still looking

## What we would like to do differently this year

1. have as much participation from analysts and the UBC ARC staff (teaching the courses)
1. have more stringent rules for faculty-delivered courses: must have hands-ons, must use our national
   systems, must send us a syllabus before a deadline; the same should apply to any GSC presentations so
   that they don’t end up promoting their own clusters
1. find a way to clearly recognize and promote faculty who support the schools / present sessions
1. have a 1h panel on career options after PhD (have HPC background, now what?), bring in people from
   different domains, put this into the program, re-use one of the lecture halls off-schedule, advertsie
   as a networking event, maybe some instructors will want to participate as well

## Recording and broadcasting

Garth Feb-27
- Garth would much prefer to use screen-capture software
- either he will travel to Vancouver, or find someone from audio/video support at UBC

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
