---
tags: OE/ALKMAT/Sztocha OE/ALKMAT/Sztocha/fontos_fogalom 
aliases: [""]
TARGET DECK: 02::Sztocha
---

# negyedrendű kumuláns
$$\begin{align}
	&\begin{aligned} 
		\kappa_4(k,m,n) =& \sigma(k,m,n)-[R_X(k)*R_X(n-m)+ \\ 
		&+ R_X(m)*R_X(n-k)+R_X(n)*R_X(m-k)]
	\end{aligned} \tag{NK.1} \\
	&\begin{aligned}
		\sigma(k,m,n) &=& E((X_t- E(X))*(X_{t+k}-E(X))*(X_{t+n}*E(X)))\\
		&=& E((X_0 - E(X))*(X_k- E(X))*(X_m - E(X))*(X_n - E(X)))
	\end{aligned} \tag{NK.2}
\end{align}$$
- $X_t$ [[tágabb értelemben stacionárius|stacionárius folyamat]]
	- $|E(X)^4| < \infty$
	- $k,m,n \in \mathbb{N}$

#Szeidl/sztochajegyzet 

# kártyák
START
Basic
Front:
negyedrendű kumuláns
Back:
$$\begin{align}
	&\begin{aligned} 
		\kappa_4(k,m,n) =& \sigma(k,m,n)-[R_X(k)*R_X(n-m)+ \\ 
		&+ R_X(m)*R_X(n-k)+R_X(n)*R_X(m-k)]
	\end{aligned} \tag{NK.1} \\
	&\begin{aligned}
		\sigma(k,m,n) &=& E((X_t- E(X))*(X_{t+k}-E(X))*(X_{t+n}*E(X)))\\
		&=& E((X_0 - E(X))*(X_k- E(X))*(X_m - E(X))*(X_n - E(X)))
	\end{aligned} \tag{NK.2}
\end{align}$$
- $X_t$ [[tágabb értelemben stacionárius|stacionárius folyamat]]
	- $|E(X)^4| < \infty$
	- $k,m,n \in \mathbb{N}$
<!--ID: 1686261277667-->
END