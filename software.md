---
layout: page
title: Software
permalink: /software/
---

## Chronus Quantum (ChronusQ)
- Principle Developer / Maintainer  2014-2018
- Contributor 2018-present
- [Github](https://github.com/liresearchgroup/chronusq_public):

ChronusQ is a production quantum chemistry software package 
written in C++11 specializing in electronic dynamics and 
relativistic effects in molecular quantum mechanics. It
was the primary deliverable from my Ph.D research and is
currently maintained by the Li Research Group.

I will contribute to the project, primarily in the context of
novel solvers for diagoanlization / inverse problems.

## CXXBLACS
- Developer / Maintainer
- [Github](https://github.com/wavefunction91/CXXBLACS)

CXXBLACS is a simple C++11 wrapper for the FORTRAN BLACS library
used in ScaLAPACK / PBLAS. It also contains wrappers for a subset
of ScaLAPACK / PBLAS and added some functionality to ease 
distributed linear algebra (distribution from node to the grid,
etc).

## HAXX
- Developer / Maintainer
- [Github](https://github.com/wavefunction91/HAXX)

HAXX (Hamilton's Quaternion Algebra for CXX) is a C++14 software
infrastructure for the development of efficient scalar and
tensorial quaternion algorithms. The novelty of HAXX is that
it contained an optimized implementation of quaternionic
matrix multiplication for AVX / AVX2. 

HAXX was the product of my MolSSI software fellowship in 2017--2018 
and is still being developed.

## PEXSI
- Contributor
- [Project Page](https://pexsi.readthedocs.io/en/latest/)

The Pole EXpansion and Selected Inversion (PEXSI) method is a fast method for
electronic structure calculation based on Kohn-Sham density functional theory.
It efficiently evaluates certain selected elements of matrix functions, e.g.,
the Fermi-Dirac function of the KS Hamiltonian, which yields a density matrix.
It can be used as an alternative to diagonalization methods for obtaining the
density, energy and forces in electronic structure calculations. The PEXSI
library is written in C++, and uses message passing interface (MPI) to
parallelize the computation on distributed memory computing systems and achieve
scalability on more than 10,000 processors.

My contribution to PEXSI has been in the development of the modern CMake build 
system.



## CMake Modules

I also curate and maintain a set of CMake modules which
target HPC software [Github](https://github.com/wavefunction91/cmake-modules).
