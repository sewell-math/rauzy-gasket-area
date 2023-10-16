# Rauzy gasket

This repository contains *rauzy-numerics.nb*, the Mathematica file used to compute/confirm numerical values for the thresholds $\delta^m$ and $\delta_m$, which are upper and lower bounds, respectively, for the infimal value of $\delta$ for which

$$ \sum_{|i| = n} \text{area}(\Delta_i)^\delta \to 0 $$

as $n \to \infty$, in page 175 of [my PhD thesis](https://wrap.warwick.ac.uk/view/author_id/347116.html).

This code can be viewed as an adaptation of that in [this other repository](https://www.github.com/sewell-math/rauzy-gasket-upper), specifically, by ignoring the diameter factors by deleting $\lambda$, or equivalently setting it to zero.

For an explanation of the background and the code, see the [wiki corresponding to this page](https://www.github.com/sewell/math/rauzy-gasket-area/wiki).

## Values obtained in rauzy-numerics.nb

m | $\delta^{m}$ | $\delta_m$
--- | --- | ---
1   | 0.8934 | 0.7681
2   | 0.8799 | 0.7766
3   | 0.8595 | 0.7862
4   | 0.8452 | 0.7938
5   | 0.8359 | 0.7995
6   | 0.8298 | 0.8035
7   | 0.8257 | 0.8063
8   | 0.8229 | 0.8083
9   | 0.8209 | 0.8098

