---
title: "Approximating Power Flow and Transmission Losses in Coordinated Capacity Expansion Problems"
date: 2020-08-26
authors: ["admin", Veit Hagenmeyer, Tom Brown]

links:
  - icon_pack: fas
    icon: book
    name: ResearchGate
    url: 'https://www.researchgate.net/publication/43887121_Approximating_Power_Flow_and_Transmission_Losses_in_Coordinated_Capacity_Expansion_Problems'
  - icon_pack: fas
    icon: code
    name: code
    url: 'https://github.com/fneum/power-flow-models'

image:
  placement: 1
  focal_point: "Smart"
---

With rising shares of renewables and the need to properly assess trade-offs
between transmission, storage and sectoral integration as balancing options,
building a bridge between energy system models and detailed power flow studies
becomes increasingly important, but is computationally challenging.

We compare approximations for two nonlinear phenomena, power flow and
transmission losses, in linear capacity expansion problems that co-optimise
investments in generation, storage and transmission infrastructure. We evaluate
different flow representations discussing differences in investment decisions,
nodal prices, the deviation of optimised flows and losses from simulated AC
power flows, and the computational performance. By using the open European
power system model PyPSA-Eur we obtain detailed and reproducible results aiming
at facilitating the selection of a suitable power flow model.

Given the differences in complexity, the optimal choice depends on the
application, the user's available computational resources, and the level of
spatial detail considered. Although the commonly used transport model can
already identify key features of a cost-efficient system while being
computationally performant, deficiencies under high loading conditions arise
due to the lack of a physical grid representation. Moreover, disregarding
transmission losses overestimates optimal grid expansion by 20%. Adding a
convex relaxation of quadratic losses with two or three tangents to the
linearised power flow equations and accounting for changing line impedances as
the network is reinforced suffices to represent power flows and losses
adequately in design studies. We show that the obtained investment and dispatch
decisions are then sufficiently physical to be used in more detailed nonlinear
simulations of AC power flow in order to better assess their technical
feasibility.