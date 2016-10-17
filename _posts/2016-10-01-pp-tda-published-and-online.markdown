---
layout: post
title:  "Relativistic pp-TDA JCTC Article Accepted and Published Online"
date:   2016-10-01 09:34:00 -0700
categories: [publication,relativity,pp-TDA,JCTC]
permalink: /posts/rel-pp-TDA
---

<script type="text/javascript"
    src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
    </script>

My recent work on the extension of the particle--particle Tamm--Dancoff
approximation (pp-TDA) to two--component relativistic Hamiltonians has been
accepted to the Journal of Chemical Theory and Computation (JCTC) The just
accepted manuscript may be found
[online](http://doi.org/10.1021/acs.jctc.6b00833).


In essence, this work discusses a simple scheme to compute the fine--structure
splittings of molecules using the pp-TDA. From the converged wavefunction of the
(+2) cation of a molecular systems, the neutral excitation energies may be
recovered via the pp-TDA. If the cation was converged using a relativistic
hamiltonian, orbitals with total angular momentum > 0 break degeneracy in a
[systematic way](https://en.wikipedia.org/wiki/Fine_structure). As such, the
pp-TDA is able to capture double ioniation potentials involving each of the
spilt orbitasl, giving rise to FSS (see the TOC graphic of the published
manuscript for a pictoral description of this procedure).

The advantange of using the pp-TDA over the ph-RPA/TDA (TDHF / CIS) is that, for
some cases, the ground and excited states may be recovered with minimal spin
contamination. It is a well known problem, especially in relativistic
hamiltonians, that spin contamination (broken spin symmetry) is apparent when
the ground state is not a singlet. Case and point being molecuar oxygen, whos HF
ground state has broken spin symmetry. These spin contamination effects can make
analysis of excited state FSS very difficult as the energetic effects may be on
the same order or larger than those of the FSS themselves. It so happens that,
especially for molecules with triplet ground states, the +2 cation is a singlet.
That is not do say that spin contamination is not present (as it should be in
relativistic hamiltonians as it does not commute with \\(S^2\\) ), but the effects are
negligible. Thus we were able to accurately capture the FSS in molecular oxygen
with the pp-TDA, a feat impractical using the ph-RPA/TDA. 

