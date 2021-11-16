---
title: "Topology-based approximations for N-1 contingency constraints in power transmission networks"
date: 2021-11-15
authors: [Amin Shokri Gazafroudi, "admin", Tom Brown]

links:
  - icon_pack: fas
    icon: book
    name: International Journal of Electrical Power & Energy Systems
    url: 'https://doi.org/10.21105/joss.03294'
  - icon_pack: fas
    icon: code
    name: Github
    url: 'https://github.com/PyPSA/condynet-2-wp-1'

image:
  placement: 1
  focal_point: "Center"
---

It is crucial for maintaining the security of supply that transmission networks continue to operate even if a single line fails. Modeling N-1 security in power system capacity expansion problems introduces many extra constraints if all possible outages are accounted for, which leads to a high computational burden. Typical approaches to avoid this burden consider only a subset of possible outages relevant to a given dispatch situation. However, this relies on knowing the dispatch situation beforehand, and it is not suitable for investment optimization problems where the generation fleet is not known in advance. In this paper, we introduce a heuristic approach to model the fully secured N-1 feasible space using a smaller number of constraints in a way that only depends on the topology of transmission networks. In our proposed approach, the network’s security is modeled by comparing the polytope of the feasible space of nodal net power obtained from the security-constrained linearized AC optimal power flow problem. To approximate this polytope, a buffer capacity factor is defined for transmission lines in the N-0 secure case, thereby avoiding the introduction of many additional constraints. In this way, three approaches are introduced for obtaining a buffer capacity factor consisting of approximate, robust and line-specific approaches. Finally, the performance of our proposed approaches is assessed in different scales of transmission networks for determining the proposed buffer capacity factors, contingency analysis and economic evaluation. Moreover, we find that our proposed heuristics provide excellent approximations of the fully secured N-1 solutions with a much lower computational burden.