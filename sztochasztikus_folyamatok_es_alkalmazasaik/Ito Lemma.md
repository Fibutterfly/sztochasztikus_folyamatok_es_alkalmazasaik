---
tags: OE/ALKMAT/Sztocha 
aliases: ["Wiener-kalkulus alaptétele", "Ito lemmában"]
---
# Ito Lemma
Minden integrálra minden rögzített $t \ge t_0$ esetén fennállnak a következő tulajdonságok:
## integrál linearitása
$$\int_{t_0}^t (a*G_1 + b*G_2) dW =\int_{t_0}^t a*G_1 dW + \int_{t_0}^t b*G_2 dW$$
ahol:
- $a,b \in \mathbb{R}$
- $G_1, G_2 \in M_2[t_0,t]$ lépcsős függvény
## Vektorintegrál
$$\int_{t_0}^t G dW = \left(\begin{array}{c}
	\sum_{k=1}^m \int_{t_0}^t G_{ik}(s)dW_s^k \\
	\vdots \\
	\sum_{k=1}^m \int_{t_0}^t G_{dk}(s)dW_s^k
\end{array} \right);
W_t = \left(\begin{array}{c}
	W_t^1 \\
	\vdots \\
	W_t^m
\end{array}\right)$$
## integrál átlaga nulla tulajdonság
Ha $E(|G(s)|) < \infty \forall t_0 \le s \le t$, akkor
$$E\left( \int_{t_0}^t G dW \right)=0$$
## Ito-Kunita formula második pontja
$E(|G(s)|)^2 < \infty \forall t_0 \le s \le t$ akkor a $d \times d$ kovarianciamátrixára fennáll
$$E\left( \int_{t_0}^t G dW * \left( \int_{t_0}^t G dW \right)^\prime \right) = \int_{t_0}^t E(G(s)*G(s)^\prime)ds$$
és
$$E\left( \left| \int_{t_0}^t G dW \right|^2 \right) = \int_{t_0}^t E(|G|^2)ds$$

#Ludwig/Szotchasztikus_differenciál 