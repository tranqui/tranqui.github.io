---
permalink: /research/
title: "Research interests"
author_profile: true
redirect_from: 
  - /research.html
---

My research can be loosely partitioned into three broad topics.

## 1. Pattern formation

![Turing patterns](/images/reactGPU.png)

In recent years I have become interested in structure formation in biology. Since early 2022 I have been trying to understand biological condensates as active droplets formed by liquid-liquid phase separation.
This work was made possible by an Alexander von Humboldt fellowship which allowed me to travel to Germany to collaborate with the [Speck group](https://www.itp4.uni-stuttgart.de/).

I recently finished the first installment in this research program, which is available as a [preprint](https://arxiv.org/abs/2406.02409).
The focus of this work is on how reaction-diffusion equations of the form

$$\partial_t \vec\rho = \vec{R} + \mathbf{D} \nabla^2 \vec\rho$$

produce patterns in the presence of conservation laws.
My approach forges an explicit connection between [Turing patterns](https://en.wikipedia.org/wiki/Turing_pattern) and field theories in active matter, which were previously considered as distinct paradigms.
In particular I have derived a universal limiting theory for pattern-formation in chemical systems that respect a conservation law.
This limiting theory reduces to "Active Model B+", a minimal active extension of the [Cahn-Hilliard model](https://en.wikipedia.org/wiki/Cahn%E2%80%93Hilliard_equation), and describes pattern formation in a fully nonlinear fashion.


## 2. Aerosol science and disease transmission

![Collection efficiency of face masks](/images/face-masks-collection-efficiency.png)


I frequently contribute theory to problems in aerosol science.
This is normally motivated by experiments peformed by my collaborators at the [Bristol Aerosol Research Centre](https://www.bristol.ac.uk/chemistry/research/barc/aerosol).
Previously I worked on the kinetics of aerosol droplets with applications to spray drying.

Following the start of the COVID-19 pandemic I became very interested in understanding to what extent face masks work at preventing disease transmission.
The relevant physics at small (micron) length-scales turns out to behave very differently from what we experience at the macroscale, and poses some novel problems in fluid mechanics.


## 3. Liquid state theory and supercooled liquids

![Many-body structures inside liquids](/images/liquid-structures.png)

Liquids are notoriously hard to model.
They are as dense as solids but lack any simplifying structure (e.g. the periodic symmetry of crystals).
Liquid-state theory has traditionally been based on [two-body correlation functions](https://en.wikipedia.org/wiki/Radial_distribution_function), which are generally assumed to capture the most important features of amorphous structure.
I have worked on extensions of liquid state theory involving *many-body correlations*, i.e. accounting for amorphous arrangements of particles inside the liquid such as the clusters sketched above.

My interest in many-body correlations was originally motivated by supercooled liquids.
In supercooled liquids the two-body measures change very little despite a dramatic 10+ orders of magnitude change in dynamical, so there appears to be a decoupling between structure and dynamics.
However, if you look at higher-order measures of structure you *do* see a change in structure.
An intriguing hypothesis is that structural features underlying dynamical arrest could be encoded in these subtle many-body correlations.

An accessible article about this work can be found in [this viewpoint](https://physics.aps.org/articles/v12/15).
