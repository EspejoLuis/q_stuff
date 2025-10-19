# Derivation of  $\displaystyle \frac{\partial C}{\partial w} = \text{Vega} \cdot \frac{1}{2\sigma T}$

In the Black–Scholes model, the call price depends on volatility $\sigma$ and maturity $T$:

$$
C = C(S_0, K, r, q, T, \sigma).
$$

We define the **total variance** as
$$
w = \sigma^2 T,
$$
so volatility can be written as
$$
\sigma = \sqrt{\frac{w}{T}}.
$$

If $T$ is fixed, the option price can be treated as a function of $w$.
Applying the chain rule gives:

$$
\frac{\partial C}{\partial w}
= \frac{\partial C}{\partial \sigma} \cdot \frac{\partial \sigma}{\partial w}.
$$

The first term is the **Vega** of the option:

$$
\frac{\partial C}{\partial \sigma} = \text{Vega}
= S_0 e^{-qT} \phi(d_1) \sqrt{T},
$$

which is always positive.

For the second term, differentiate $\sigma = \sqrt{w/T}$ with respect to $w$:

$$
\frac{\partial \sigma}{\partial w}
= \frac{1}{2\sqrt{wT}}
= \frac{1}{2\sigma T}.
$$

Combining both results:

$$
\frac{\partial C}{\partial w}
= \text{Vega} \cdot \frac{1}{2\sigma T}.
$$

Since Vega, $\sigma$, and $T$ are all positive,
$$
\frac{\partial C}{\partial w} > 0.
$$
