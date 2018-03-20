---
layout: default
title: Databases course
nav: false
---

**Instructor**: Wolfgang Richter (SFU)

**Title**: Databases

Introduction to databases on Cedar.

**Target audience**: general

**Course plan**:


1. overview of the two database servers on Cedar: cedar-mysql-vm (MariaDB MySQL v.10.2) and
   cedar-pgsql-vm (PostgreSQL v.10.1 with PostGIS v.2.4)
1. deeper dive into MySQL on Cedar
  - how to get an MySQL account and database on the server for your research
  - new features offered by this recent flavour of MySQL called MariaDB
  - how to use the _mysql_ interactive client from the Compute Canada headnode to interactively issue SQL
    commands or simply pipe in a set of commands to be executed
  - other ways to use the service such as writing a Python script, Perl, etc.
  - tips on optimizing your SQL commands; importance of creating indexes; explain a long running command
    to see where it can be optimized
1. deeper dive into PostgreSQL on Cedar
  - how to get a Postgres account and database on the server for your research
  - new features offered by this recent version of Postgres
  - how to use the _psql_ client from the Compute Canada headnode to interactively issue SQL commands or
    simply pipe in a set of commands to be executed
  - other ways to use the service such as writing a Python script, Perl, etc.
  - tips on optimizing your SQL commands; importance of creating indexes; explain a long running command
    to see where it can be optimized


**Duration**: 3 hours

**Level**: beginner

**Prerequisites**:

**Background information**: The database services in WestGrid are now offered through high-performance
database MySQL and Postgres servers on Cedar. There is a
[documentation draft](https://docs.computecanada.ca/wiki/Database).
