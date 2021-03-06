---
title: toolchains
permalink: /toolchains/
layout: single
date:  2020-02-01
sidebar:
  nav: "docs"
---

Most software packages are built from a compiler toolchain. A toolchain consists of one or more compilers, 
together with some libraries for using an MPI stack and commonly used math libraries. Well-known packages
include BLAS/LAPACK APIs for linear algebra routines.

EasyBuild supports several different toolchains. The Hutch uses the foss toolchain, which
is an acronym for Free Open Source Software. Foss is based on the GNU compiler tools.
Toolchains are curated twice a year and named for the year, and labeled a or b, i.e., foss-2019b.
When loading multiple modules for a workflow, always load tools from the same toolchain. Do not mix and
match tools from different toolchains.

## GNU Toolchain Versions

| Toolchain | GCC Version | Notes |
| ----------|-------------| ---------|
| [foss-2020b]({{ site.baseurl }}/foss-2020b/) | GCC 10.2.0 | Begining Nov 2020 | 
| foss-2020a | GCC 9.3.0 | Mostly skipped | 
| [foss-2019b]({{ site.baseurl }}/foss-2019b/) | GCC 8.3.0 | Primay tool chain for June 2019 cluster update |
| foss-2019a | GCC 8.2.0 | skipped |
| [foss-2018b]({{ site.baseurl }}/foss-2018b/) | GCC 7.3.0 | Many modules were built for the new cluster, but were outdated by 2019 |
| foss-2016b | GCC 5.4.0 | Ubuntu 14.04 cluster |
|------------|-----------|-------------|


