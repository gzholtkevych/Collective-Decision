
----
[[index|Jump to index]]

----
<H1>How does a community participant decide?</H1>

----

## Uncertainty about the choice

Let $\pvec{w}\in\Delta_m$ be a preference vector of a community participant then the function
$$h(\pvec{w})=-\dfrac1{\log_2 m}\cdot\sum_{i=1}^m w_i\cdot\log_2 w_i$$
varies between $0$ and $1$, equals $0$ only if $w_i=1$ for some $i=1,\ldots,m$, and equals $1$ only if $\pvec{w}=\big(\frac1m,\ldots,\frac1m\big)$.

This function can be seen as a measure of the participant's uncertainty about the choice.
It is reasonable that the participant's disclaiming probability is greater if the value of the function is greater.

## Probability of a decision

We believe that the propensity to decision-making for each community participant is individual and characterized by a positive real number $\alpha$.

Based on this, we propose to calculate the probability of refusal to make a decision using the following formula$$\Pr(0\mid\pvec{w})=h(\pvec{w})^\alpha.$$

In this case, to calculate the probability of deciding $i\in\dec$, the following formula is used$$\Pr(i\mid\pvec{w})=(1-h(\pvec{w})^\alpha)\cdot w_i.$$