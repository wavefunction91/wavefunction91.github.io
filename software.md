---
layout: page
title: Software
permalink: /software/
---

## QDK/Chemistry
- Lead Architect / Group Lead
- [Github](https://github.com/microsoft/qdk-chemistry)
- [Documentation](https://microsoft.github.io/qdk-chemistry)

QDK/Chemistry is an open-source C++/Python toolkit, part of the Microsoft Quantum
Development Kit (QDK), that connects classical electronic structure methods to
chemistry-aware quantum algorithms for quantum computing applications.


## GauXC
- Principal Developer / Maintainer 2019-present
- [Github](https://github.com/wavefunction91/GauXC)

GauXC is a modern C++ library for massively parallel, GPU accelerated Gaussian basis
DFT simulations. It is the primary DFT driver for the NWChemEX project as well
as various others (MPQC, etc).


## ExchCXX
- Principal Developer / Maintainer 2019-present
- [Github](https://github.com/wavefunction91/ExchCXX)

ExchCXX is a modern C++ library for GPU accelerated evaluation of exchange-correlation functionals required for DFT simulations. It is the underlying XC implementation
for GauXC, but can be used for any software which requires spacial evaluation of
XC functions on GPU accelerators.


## IntegratorXX
- Principal Developer / Maintainer
- [Github](https://github.com/wavefunction91/IntegratorXX)

IntegratorXX is a modern C++ library for the generation of numerical quadratures,
including the atomic and molecular integration grids used in DFT simulations.


## MACIS
- Principal Developer / Maintainer
- [Github](https://github.com/wavefunction91/MACIS)

MACIS (Many-Body Adaptive Configuration Interaction Suite) is a modern C++ library
for massively parallel, distributed memory selected configuration interaction
methods, including the adaptive sampling CI (ASCI) method.




## NWChemEx
- Contributor 2018-2024
- [Github](https://github.com/NWChemEx)

NWChemEx is a quantum chemistry code originally funded by the DOE Exascale Computing Project (ECP). My contributions have
been in the development of their density functional theory implementation
as well as in the integration of scalable linear algebra solvers suitable
for exascale computing.

## Chronus Quantum (ChronusQ)
- Principal Developer / Maintainer  2014-2018
- Contributor 2018-2024
- [Github](https://github.com/xsligroup/chronusq_public)

ChronusQ is a production quantum chemistry software package 
written in C++11 specializing in electronic dynamics and 
relativistic effects in molecular quantum mechanics. It
was the primary deliverable from my Ph.D research and is
currently maintained by the Li Research Group.


## TiledArray
- Contributor (2020-2024)
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

HAXX was the product of my MolSSI software fellowship in 2017--2018.

## PEXSI
- Contributor 2018-2024
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
