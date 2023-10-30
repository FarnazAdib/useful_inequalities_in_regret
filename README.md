# useful_inequalities_in_regret
- Select $H=(1/\gamma) \log T$. Then, we have $(1-\gamma)^H \leq e^{-\gamma H}=e^{-\log T}=\frac{1}{T}$.
- All polylogaritmics $(\log T)^n,\:n \geq 1$ are of order $\mathcal{O}(T^{\epsilon}), \epsilon>0$. One common choice is $\epsilon =0.5$
- Geometric series: $\frac{1}{1-x}=\sum_{i=0}^{\infty}x^i$. Take $x=1-\gamma$ where $\gamma <1$. Then, we have $\sum_{i=0}^{n}(1-\gamma)^{i} < \frac{1}{\gamma}$.
- $1+x < e^{x}$.