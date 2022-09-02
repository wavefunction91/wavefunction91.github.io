---
layout: page
title: Software
permalink: /software/
---

## GauXC
- Principle Developer / Maintainer 2019-present
- [Github](https://github.com/wavefunction91/GauXC)

GauXC is a modern C++ library for massively parallel, GPU accelerated Gaussian basis
DFT simulations. It is the primary DFT driver for the NWChemEX project as well
as various others (MPQC, etc).


## ExchCXX
- Principle Developer / Maintainer 2019-present
- [Github](https://github.com/wavefunction91/GauXC)

ExchCXX is a modern C++ library for GPU accelerated evaluation of exchange-correlation functionals required for DFT simulations. It is the underlying XC implementation
for GauXC, but can be used for any software which requires spacial evaluation of
XC functions on GPU accelerators.




## NWChemEx
- Contributor 2018-present
- [ECP Website](https://www.exascaleproject.org/project/nwchemex-tackling-chemical-materials-and-biomolecular-challenges-in-exascale/)

NWChemEx is an ECP funded quantum chemistry code. My contributions have
been in the development of their density functional theory implementation
as well as in the integration of scalable linear algebra solvers suitable
for exascale computing.

## Chronus Quantum (ChronusQ)
- Principle Developer / Maintainer  2014-2018
- Contributor 2018-present
- [Github](https://github.com/liresearchgroup/chronusq_public)

ChronusQ is a production quantum chemistry software package 
written in C++11 specializing in electronic dynamics and 
relativistic effects in molecular quantum mechanics. It
was the primary deliverable from my Ph.D research and is
currently maintained by the Li Research Group.

I will contribute to the project, primarily in the context of
novel solvers for diagoanlization / inverse problems.


## TiledArray
- Contributor (2020-present)
- [Github](https://github.com/ValeevGroup/tiledarray)

TiledArray is a distributed memory tensor contraction library developed
by the Valeev group at Virginia Tech. My primary contributions to TiledArray
have been in the development of interfaces for TiledArray data structures
to high-performance linear algebra software (e.g. ScaLAPACK, SLATE, etc).

## scalapackpp
- Developer / Maintainer
- [Github](https://github.com/wavefunction91/scalapackpp)

scalapackpp is a C++17 wrapper around the ScaLAPACK distributed
memory linear algebra package.


## blacspp
- Developer / Maintainer
- [Github](https://github.com/wavefunction91/blacspp)

blacspp is a C++17 wrapper around the BLACS library utilized
in distributed memory linear algebra software (e.g. ScaLAPACK)


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
- Contributor 2018-present
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
