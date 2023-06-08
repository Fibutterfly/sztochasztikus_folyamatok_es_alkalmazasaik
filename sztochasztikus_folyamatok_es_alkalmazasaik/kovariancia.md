---
tags: OE/ALKMAT/Sztocha OE/ALKMAT/Sztocha/fontos_fogalom 
aliases: ["korreláció", "kovariancia mátrix"]
TARGET DECK: 02::Sztocha
---

# kovariancia
$$\begin{align}
	\begin{aligned}COV(X,Y) &= E[(X-E(X))*(Y-E(Y))] =\\
	 &= E(X*Y) - E(X)*E(Y) \end{aligned}\tag{K.1}
\end{align}$$
- $X,Y$ [[valószínűségi változó]]
	- $|E(X)^2|,|E(Y)^2| < \infty$

#Szeidl/sztochajegyzet 

# korreláció
$$\begin{align}
	CORR(X,Y) = \dfrac{COV(X,Y)}{D(X)*D(Y)} \tag{K.2}
\end{align}$$
- $X,Y$ [[valószínűségi változó|valószínűségi változók]]
	- $|D(X)|, |D(Y)| < \infty$
	- $VAR(X), VAR(Y) > 0$

#Szeidl/sztochajegyzet 

# kovariancia mátrix
$$\begin{align}
	\mu_X = E(X) = (E(X_1), \dots, E(X_n))^T \tag{K.3} \\
	R_X = E[(X-E(X))*(X-E(X))^T]=(COV(X_i,X_j))_{i,j=1}^n \tag{K.4}
\end{align}$$
- $X$ [[valószínűségi változó]] (vektor)
	- $|D(X)| < \infty$

#Szeidl/sztochajegyzet 

# Kártya
START
Basic
Front:
Kovariancia
Back:
$$\begin{align}
	\begin{aligned}COV(X,Y) &= E[(X-E(X))*(Y-E(Y))] =\\
	 &= E(X*Y) - E(X)*E(Y) \end{aligned}\tag{K.1}
\end{align}$$
- $X,Y$ [[valószínűségi változó]]
	- $|E(X)^2|,|E(Y)^2| < \infty$
<!--ID: 1686258280463-->
END

START
Basic
Front:
korreláció
Back:
$$\begin{align}
	CORR(X,Y) = \dfrac{COV(X,Y)}{D(X)*D(Y)} \tag{K.2}
\end{align}$$
- $X,Y$ [[valószínűségi változó|valószínűségi változók]]
	- $|D(X)|, |D(Y)| < \infty$
	- $VAR(X), VAR(Y) > 0$
<!--ID: 1686258572210-->
END

START
Basic
Front:
kovariancia mátrix
Back:
$$\begin{align}
	\mu_X = E(X) = (E(X_1), \dots, E(X_n))^T \tag{K.3} \\
	R_X = E[(X-E(X))*(X-E(X))^T]=(COV(X_i,X_j))_{i,j=1}^n \tag{K.4}
\end{align}$$
- $X$ [[valószínűségi változó]] (vektor)
	- $|D(X)| < \infty$
<!--ID: 1686258940487-->
END