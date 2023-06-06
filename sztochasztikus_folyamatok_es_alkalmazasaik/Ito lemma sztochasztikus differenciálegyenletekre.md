---
tags: OE/ALKMAT/Sztocha 
aliases: [""]
---
# [[Ito lemma]] sztochasztikus differenciálegyenletekre
$$
\begin{aligned}
	\dfrac{\delta}{\delta t}u(t,x)&=u_t& \\
	\dfrac{\delta}{\delta x_i}u(t,x)&= u_{x_i} & x = (x_1, \dots, x_d) \\
	\dfrac{\delta^2}{\delta x_i \delta x_j} u(t,x) &= u_{x_i x_j} & i,j\le d
\end{aligned}
$$
Ahol:
- $u:(t,x) \to \mathbb{R}^k$
	- folytonos
	- minden $k$ dimenziós vektorértékű parciális deriváltjai is folytonosak
- $t \in [t_0, T]$
- $x \in \mathbb{R}^d$.

Legyen a következő [[sztochasztikus differenciál|sztochasztikus differenciál egyenlet]]:
$$d X_t = f(t)dt + G(t) d W_t$$
ahol:
- $X_t$ az $d$ dimenziós [[Sztochasztikus folyamatok|sztochasztikus folyamat]] $[t_0, T]$-ben
- $W_t$ pedig $m$ dimenziós [[standard wiener folyamat|Wiener-folyamat]].

Akkor tudjuk értelmezni a
$$Y_t = u(t, X_t)$$
$k$ dimenziós folyamatot. Amelynek a kezdeti értéke $Y_{t_0} =u(t_0,X_{t_0})$.

Az előző folyamatra igaz a következő összefüggés:
$$
\begin{aligned}
	d Y_t = & \bigg[ u_t(t, X_t) + u_x(t,X_t) * f(t) + \\
	&+ \dfrac{1}{2} * \sum_{i=1}^d \sum_{j=1}^d u_{x_i, x_j}(t,X_t)  (*G(t)*G(t)^\prime_{ij})
	\bigg]dt + \\
	&+u_x(t,X_t)*G(t) dW_t
\end{aligned}
$$.
Ezt írhatjuk egy kicsit egyszerűbb formában:
$$
\begin{aligned}
	d Y_t = & \bigg[ u_t(t, X_t) + u_x(t,X_t) * f(t) + \\
	&+ \dfrac{1}{2} * tr(G*G^\prime*u_{xx})
	\bigg]dt + \\
	&+u_x(t,X_t)*G(t) dW_t \\
	tr =& \sum_{i=1}^d \sum_{j=1}^d u_{x_i, x_j}(t,X_t)  (*G(t)*G(t)^\prime_{ij})
\end{aligned}
$$
Ahol:
- $u_x = (u_{x1}, \dots, u_{xk})$ $k \times d$ méretű mátrix
- $u_{x_i x_j}$ pedig $k$ dimenziós oszlop vektor
- $u_{x x} = (u_{x_i x_j})$ $d \times d$ méretű mátrix, amelynek elemei $k$ dimenziós vektorok.

#Ludwig/Szotchasztikus_differenciál 