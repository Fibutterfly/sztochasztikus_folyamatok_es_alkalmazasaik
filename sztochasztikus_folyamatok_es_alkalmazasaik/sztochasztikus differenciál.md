---
tags: OE/ALKMAT/Sztocha 
aliases: ["sztochasztikus differenciál egyenlet"]
---
# sztochasztikus differenciál
$$X_t(\omega) = X_{t_s}(\omega) + \int_{t_0}^t f(s, \omega)ds + \int_{t_0}^t G(s, \omega) dW_s(\omega)$$
Ahol:
- $W_t$ egy $m$ dimenziós [[standard wiener folyamat|Wiener-folyamat]]
- $G \in M_2^{d,m}[t_0, T]$
- $X_{t_s}$ [[Sztochasztikus folyamatok|sztochasztikus folyamat]]
	- független $W_t - W_{t_0}, t \ge t_0$ -tól
- $f$ függvény
	- független $W_t - W_{t_0}, t \ge t_0$ -tól
	- $R^d$ értékű
	- jövőtől nem függő
	- $1$ valószínűséggel érvényes, hogy: $\int_{t_0}^T |f(s, \omega)|ds < \infty$ 
- $\omega$ a mintatér eleme, azaz egy adott kimenet az eseményteret alkotó $\sigma$-algebra egy eleme
- $s$ a függvény értékelésének az időpillanata.
- $d$  véges differenciálás lépése.
- $m$ az a [[standard wiener folyamat|Wiener-folyamat]] dimenziója. Ha egy [[standard wiener folyamat|Wiener-folyamat]] $m$ dimenziós, akkor azt jelenti, hogy az $m$ darab független standard [[standard wiener folyamat|Wiener-folyamatot]] összefűztük egy $m$ dimenziós vektorban.

#Ludwig/Szotchasztikus_differenciál 
## jelölése és értelmezése
$$dX_t = f(t)dt + G(t) dW_t = fdt + G dW$$
$$X_t - X_s = \int_s^t f(u)du + \int_s^t G(u)dW_u$$