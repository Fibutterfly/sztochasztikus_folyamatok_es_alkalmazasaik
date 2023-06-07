---
tags: OE/ALKMAT/Sztocha OE/ALKMAT/Sztocha/2tétel 
aliases: ["kovarianciafüggvényére"]
TARGET DECK: 02::Sztocha
---
# kovarianciafüggvény
$$ \begin{align}

	\begin{aligned}R_X(s,t)&= \\R_X(u) &= \operatorname{cov}(X_t, X_{t-u}) \\
	
		&= E[(X_t - E(X_t))(X_{t-u}-E(X_{t-u}))]
	\end{aligned} \tag{K.1}
\end{align} $$
Ez itt nem a kovarianciamátrixot fogja vissza adni, hanem az eltérés közötti összefüggést.
#Szeidl/sztochajegyzet 

# Kovarianciafüggvény tulajdonságai
1. **Additivitás**: Ha $X$ és $Y$ véletlen változók és $a$ és $b$ valós számok, akkor a kovarianciafüggvény additív, azaz:
$$cov(aX + bY, Z) = a*cov(X, Z) + b*cov(Y, Z)$$

2. **Szimmetria**: A kovarianciafüggvény szimmetrikus, azaz
$$cov(X,Y) = cov(Y,X)$$

3. **Állandóság**: Ha $X$ és $Y$ véletlen változók és $a$ és $b$ konstansok, akkor a kovarianciafüggvény állandó marad, ha mindkét változót $a$-val és $b$-vel eltoljuk. Azaz,
$$cov(X + a, Y + b) = cov(X, Y)$$

4. **Nemnegativitás**: A kovarianciafüggvény mindig nemnegatív, azaz

$$cov(X, X) \ge 0$$

Ha a két változó független, akkor az egyenlőség akkor és csak akkor áll fenn, ha az $X$ állandó.

5. Ha $X$ és $Y$ együttesen normális eloszlásúak, akkor a kovarianciafüggvény teljesen meghatározza a két változó közötti kapcsolatot.

6. **Két független változó kovarianciája nulla**: Ha $X$ és $Y$ független változók, akkor a kovarianciafüggvényük zérus:

$$cov(X, Y) = 0$$

7. A második momentumnak léteznie kell.

# Kovarianciafüggvény becslése
A becsléshez használt összefüggések a következőek:
$$
\begin{aligned}
	\hat{R}_{1,k} = \cfrac{1}{T}\sum_{j=1}^{T -|k|}(X_j - \mu_X)(X_{j+|k|} -\mu_X) \\
	\bar{R}_{1,k} = \cfrac{1}{T-|k|} \sum_{j=1}^{T - |k|}(X_j - \mu_X)(X_{j+ |k|} - \mu_X) 
\end{aligned}$$
Ahol:
- $T$ hosszú folyamatunk van
- $k$ a "késeltetés" két megfigyelés között
- $\mu_X$ a [[várható érték]], ha ez nem ismert érdemes becsülni.

# kártya
START
Basic
Front:
Kovariancia függvény
Back:
$$ \begin{align}

	\begin{aligned}R_X(s,t)&= \\R_X(u) &= \operatorname{cov}(X_t, X_{t-u}) \\
	
		&= E[(X_t - E(X_t))(X_{t-u}-E(X_{t-u}))]
	\end{aligned} \tag{K.1}
\end{align} $$
<!--ID: 1686162748470-->
END