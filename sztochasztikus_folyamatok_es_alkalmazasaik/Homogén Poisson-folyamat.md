---
tags: OE/ALKMAT/Sztocha OE/ALKMAT/Sztocha/1tétel
aliases: [""]
TARGET DECK: 02::Sztocha
---

# Homogén Poisson folyamat konstrukciója
$$\begin{align}
	&N_0 = 0 \tag{HPF.1} \\
	&N_t = \sum_{i=1}^\infty I(T_i \le t) \tag{HPF.2}
\end{align}$$
- $T_i, i=1,2, \dots$ események bekövetkezéseinek időpontjai 
	- egymás utáni bekövetkezések között eltelt időtartamok függetlenek, $\lambda$ paraméterű exponenciális eloszlású [[valószínűségi változó]]

#Szeidl/sztochajegyzet 

# Homogén Poisson folyamat
$$\begin{align}
	P(N(t)-N(s)=k) = \dfrac{(\Lambda(t) - \Lambda(s))^k}{k!} e^{-(\Lambda(t) - \Lambda(s))} \tag{HPF.3}
\end{align}$$
- $N(t)$ az adott időpontba vett értékek
	- $N(0)=0$
	- $N(t)-N(s)$ függetlenek 
- $k \in \mathbb{N}$
- $0 \le s < t$
- $\{ \Lambda(t), t \ge 0 \}$
	- nem negatív
	- monoton nem csökkenő
	- balról folytonos
	- $\Lambda(0) = 0$
	- ez a paraméter $(\Lambda(t) - \Lambda(s))$

# kártyák
START
Basic
Front:
Homogén Poisson folyamat konstrukciója
Back:
$$\begin{align}
	&N_0 = 0 \tag{HPF.1} \\
	&N_t = \sum_{i=1}^\infty I(T_i \le t) \tag{HPF.2}
\end{align}$$
- $T_i, i=1,2, \dots$ események bekövetkezéseinek időpontjai 
	- egymás utáni bekövetkezések között eltelt időtartamok függetlenek, $\lambda$ paraméterű exponenciális eloszlású [[valószínűségi változó]]
<!--ID: 1686078152790-->
END

START
Basic
Front:
Homogén Poisson folyamat
Back:
$$\begin{align}
	P(N(t)-N(s)=k) = \dfrac{(\Lambda(t) - \Lambda(s))^k}{k!} e^{-(\Lambda(t) - \Lambda(s))} \tag{HPF.3}
\end{align}$$
- $N(t)$ az adott időpontba vett értékek
	- $N(0)=0$
	- $N(t)-N(s)$ függetlenek 
- $k \in \mathbb{N}$
- $0 \le s < t$
- $\{ \Lambda(t), t \ge 0 \}$
	- nem negatív
	- monoton nem csökkenő
	- balról folytonos
	- $\Lambda(0) = 0$
	- ez a paraméter $(\Lambda(t) - \Lambda(s))$
<!--ID: 1686078152799-->
END