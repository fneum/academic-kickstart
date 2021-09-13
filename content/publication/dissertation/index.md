---
title: "Computational and Near-Optimal Trade-Offs in Renewable Electricity System Modelling"
date: 2021-09-13
authors: ["admin"]

links:
  - icon_pack: fas
    icon: book
    name: Dissertation in KITopen
    url: 'https://doi.org/10.5445/IR/1000137267'

image:
  placement: 1
  focal_point: "Center"
---

In the decades to come, the European electricity system must undergo an unprecedented transformation to avert the devastating impacts of climate change. To devise various possibilities for achieving a sustainable yet cost-efficient system, in the thesis at hand, we solve large optimisation problems that coordinate the siting of generation, storage and transmission capacities. Thereby, it is critical to capture the weather-dependent variability of wind and solar power as well as transmission bottlenecks. In addition to modelling at high spatial and temporal resolution, this requires a detailed representation of the electricity grid. However, since the resulting computational challenges limit what can be investigated, compromises on model accuracy must be made, and methods from informatics become increasingly relevant to formulate models efficiently and to compute many scenarios.

The first part of the thesis is concerned with justifying such trade-offs between model detail and solving times. The main research question is how to circumvent some of the challenging non-convexities introduced by transmission network representations in joint capacity expansion models while still capturing the core grid physics. We first examine tractable linear approximations of power flow and transmission losses. Subsequently, we develop an efficient reformulation of the discrete transmission expansion planning (TEP) problem based on a cycle decomposition of the network graph, which conveniently also accommodates grid synchronisation options. Because discrete investment decisions aggravate the problem's complexity, we also cover simplifying heuristics that make use of sequential linear programming (SLP) and retrospective discretisation techniques.

In the second half, we investigate other trade-offs, namely between least-cost and near-optimal solutions. We systematically explore broad ranges of technologically diverse system configurations that are viable without compromising the system's overall cost-effectiveness. For example, we present solutions that avoid installing onshore wind turbines, bypass new overhead transmission lines, or feature a more regionally balanced distribution of generation capacities. Such alternative designs may be more widely socially accepted, and, thus, knowing about these degrees of freedom is highly policy-relevant. The method we employ to span the space of near-optimal solutions is related to modelling-to-generate-alternatives, a variant of multi-objective optimisation. The robustness of our results is further strengthened by considering technology cost uncertainties. To efficiently sweep the cost parameter space, we leverage multi-fidelity surrogate modelling techniques using sparse polynomial chaos expansion in combination with low-discrepancy sampling and extensive parallelisation on high-performance computing infrastructure.