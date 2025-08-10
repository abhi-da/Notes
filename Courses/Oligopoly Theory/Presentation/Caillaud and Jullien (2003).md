[Link To the Paper](https://doi.org/10.2307/1593720)

**Chicken & Egg problem** : to attract buyers, an intermediary should have a large
base of registered sellers, but these will be willing to register only if they expect many buyers to
show up.

Why name Chicken and Egg? Who came first? Chicken requires egg for hatching, Egg requires chicken to lay them.

The article analyses markets which accounts for - network externalities (more buyer attract more sellers) , non-exclusivity of services (anybody can join any no. of platforms) and price discrimination (different price for different sellers or buyers, like giving discount coupon to new users).

Paper makes two contributions: 
- Determines equilibrium market structures that are likely to emerge and characterises their efficiency properties. 
- Provides precise description and analysis of the pricing strategies that allow inter-mediation service providers to protect their business or gain new business. 

#### Model

They use a pairwise matching model with two homogeneous populations. For a given agent, there exists a unique matching partner on the other side of the market with whom trade is valuable. Matched partner follow an efficient bargaining process to determine the transaction price.  Something like a marriage platform (shaadi.com) 

A given j-agent has zero probability of finding his matching partner by just picking randomly within the i-population. But he can turn to an intermediary endowed with an information technology that can perform match-making services. 

Two matchmakers, each having cost $c_i$ of providing service to one i-agent. They have the same technology. The intermediaries can price discriminate using two pricing instruments:

- can charge user *i* with $p^i$ registration fee (if negative, can be seen as welcome bonus)
- can charge total transaction fee $t^k$ conditional on occurrence of the trade. $0 \geq t^k$ .

A two stage model: 
1. Matchmakers set price $P^k$ simultaneously and non-cooperatively and is publicly observable
2. Users simultaneously choose which match-maker to register with.  

Utility of user *i* is given by: $U_i$= $(n_j)^k u_i (1-t^k) - (p_i)^k$ 

Profit for match-maker is given by:  $\Pi^k = \sum_i \left[ n_i^k (p_i^k - c_i) \right] + \lambda n_1^k n_2^k t^k$ , $n_i$ are distribution of agents across match-makers. k= {I, E} (two match making sites)

**Proposition 1:** If only single homing is allowed, the only equilibrium are dominant firm equilibrium, where one intermediary firm *i* captures all users, charges maximal transaction fee ($t^i=1$), subsidies registration and makes zero profit. 