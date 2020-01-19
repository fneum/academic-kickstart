---
title: "Transmission Expansion Planning with Linear Optimal Power Flow Using Cycle Flows"
date: 2019-10-08
authors: ["admin"]

links:
  - icon_pack: fas
    icon: microphone
    name: presentation @ Georgia Institute of Technology (October 2019)
    url: 'https://www.neumann.fyi/files/cycletep.pdf'
  - icon_pack: fas
    icon: microphone
    name: presentation @ Los Alamos National Laboratory (October 2019)
    url: 'https://www.neumann.fyi/files/cycletep.pdf'
  - icon_pack: fas
    icon: code
    name: code
    url: 'https://github.com/fneum/ev_chargingcoordination2017'
---

Linear optimal power flow (LOPF) formulations use a linearization of the
AC load flow equations. The common formulation uses voltage angles at
the buses as auxiliary optimization variables, but alternatives can be
computationally advantageous.

It is possible to circumvent the auxiliary voltage angle
variables by expressing Kirchhoff's voltage law based on a cycle basis
of the network graph. In computationally challenging benchmarks such as
multi-period LOPF with storage dispatch and generation capacity
expansion, this formulation incurred speed-ups by an order of magnitude.

Including transmission expansion planning (TEP) adds to the problem
complexity as it is bilinear (unless using a big-M disjunctive
relaxation) due to the dependence of line expansion on line impedance
and nonconvex because of a discrete set of line expansion options.

This talk will guide through a derivation of a cycle-based mixed-integer
  linear formulation of the transmission expansion planning (TEP)
problem instead of using an angle-based formulation and will motivate
why it is necessary for spatially and temporally resolved energy system
models that co-optimize generation, transmission and storage infrastructure.