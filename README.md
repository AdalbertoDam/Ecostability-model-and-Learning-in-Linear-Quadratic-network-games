### Ecostability model and Learning in Linear Quadratic network-games

In the context of Network Games, the linear quadratic model has been extensively
used to model strategic interactions between a group of individuals or organisa-
tions. Due to its intrinsic simplicity, it allows to study games where a player’s
payoff not only depends on his own action but also on those of their neighbors,
in an underlying network structure, with numerous potential applications in eco-
nomics and social sciences. When all players have full and perfect knowledge of
the game, including the rules, possible strategies, payoffs, and the actions taken by
other players, the analysis of Nash equilibria can be done by studying the topologi-
cal properties of the network (1). However, in more realistic scenario, it is common
to observe uncertainty on both the network structure and game properties, leading
to the study of a generalized game where a player lacks information on who he’s
interacting with, and the strength of his externalities. The best response is then
based on a subjective beliefs: we imagine that an agent is unaware of the identity
of her neighbors and she receives only an aggregate contribution she best responds
to in order to maximize her utility. The learning process leads to conjectural best
response paths that may possibly converge to a steady state, which represents a
generalization of the equilibrium state, called Self-Confirming Equilibrium (SCE)
(2). When only local externalities are present, the SCE set can be characterized by
means of the Nash equilibrium of the auxiliary game with complete information
where only active agents are present, this is related to the fact that if an agent be-
comes inactive after a certain time period of the learning dynamics, it will remain
inactive for the rest of the game. As a consequence, the outcome of the learning
process will result in a portion of the community that will reach an inactive ab-
sorbing state, while the rest will, possibly, converge to a steady state. A similar
scenario can be observed in the study of the generalized Lotka-Volterra equations,
which are frequently used to describe the dynamics of predator-prey interactions
in ecology. Similarly to the linear quadratic model, one must analyze the dynamics
of N interacting degrees of freedom, which is in principle deterministic once the
initial conditions and network topology are fixed. To focus on typical properties of
the community, the ecosystem can be treated as the outcome of a random choice,
within a statistical ensemble of possible network structures: random Lotka-Volterra
equations can then be recasted into a 1 body self-consistent stochastic dynamics
through a dynamical mean field theory approach in the thermodynamical limit (3),
averaging over all possible sources of uncertainty. In ecology, one finds a region in
which one competitive equilibrium exists and one region in which the total biomass
in the system explodes as a consequence of unbalanced interactions. In this work
the linear quadratic model is analysed with the same approach, focusing on the
role of anticorrelated and mutualistic interactions, stability and connectivity of the
network. Similarly to the case of ecological communities, it is shown that under
some conditions on the structure of the network, the learning process can lead to
inactivity traps, in which a, possibly large, fraction of the network does not con-
tribute to the system. Non-cooperative interactions surprisingly promote stability,
while also favouring an increasing fraction of surviving agents at the steady state.
Connectivity plays a crucial role in the outcomes of the learning process, promoting
as well the stability of the community.

This repository contains all the computational work performed fot the Master Thesis project described above in the course of Physics of 
Complex Systems at Politecnico of Torino.
The learning process for the linear quadratic game is implemented in python and the results of simulations 
are compared with the theoretical results obtained similarly to what is found for disordered systems (3).


(1) Ballester, C., Calvò-Armengol, A., and Zenou, Y. (2006). Who’s who in net-
works. Wanted:the key player. Econometrica, Vol. 74, No. 5 (2006), 1403–1417.
(2) Fudenberg, D., and Levine, D. K., The Theory of Learning in Games; The MIT
press: 1998.
(3) Galla, T. (2018). Dynamically evolved community size and stability of random
Lotka-Volterra ecosystems. EPL, Vol 13, 48004
