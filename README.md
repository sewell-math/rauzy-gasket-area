# Rauzy gasket

This repository contains *rauzy-area.nb*, the Mathematica file used to confirm numerical estimates for $\delta^m$ and $\delta_m$, which are upper bounds for the infimal value of $\delta$ for which

$$ \sum_{|i| = n} \text{area}(\Delta_i)^\delta \to 0 $$

as $n \to \infty$, in page 175 of [my PhD thesis](https://wrap.warwick.ac.uk/view/author_id/347116.html) and also in an upcoming preprint.

This code is an adaptation of that in [this other repository](https://www.github.com/sewell-math/rauzy-gasket-upper), specifically, by ignoring the diameter factors by deleting $\lambda$, or equivalently setting it to zero. For more details, see the [corresponding wiki](https://www.github.com/sewell-math/rauzy-gasket-upper/wiki) and above mentioned thesis.


*** Values obtained

m | $\delta^{m}$
--- | ---
1   | 0.8934
2   | 0.8799
3   | 0.8595
4   | 0.8452
5   | 0.8359
6   | 0.8298
7   | 0.8257
8   | 0.8229
9   | 0.8209
