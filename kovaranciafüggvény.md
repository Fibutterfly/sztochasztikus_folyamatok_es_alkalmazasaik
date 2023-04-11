---
tags: OE/ALKMAT/Sztocha 
aliases:
---
# kovarianciafüggvény
$$ \begin{aligned}

R_X(u) &= \operatorname{cov}(X_t, X_{t-u}) \\

&= E[(X_t - E(X_t))(X_{t-u}-E(X_{t-u}))]

\end{aligned} $$
Ez itt nem a kovarianciamátrixot fogja vissza adni, hanem az eltérés közötti összefüggést.
#Szeidl/sztochajegyzet 

# Kovarianciafüggvény tulajdonságai
1. **Additivitás**: Ha $X$ és $Y$ véletlen változók és $a$ és $b$ valós számok, akkor a kovarianciafüggvény additív, azaz:
$$cov(aX + bY, Z) = a_cov(X, Z) + b_cov(Y, Z)$$

2. **Szimmetria**: A kovarianciafüggvény szimmetrikus, azaz
$$cov(X,Y) = cov(Y,X)$$

3. **Állandóság**: Ha $X$ és $Y$ véletlen változók és $a$ és $b$ konstansok, akkor a kovarianciafüggvény állandó marad, ha mindkét változót $a$-val és $b$-vel eltoljuk. Azaz,
$$cov(X + a, Y + b) = cov(X, Y)$$

4. **Nemnegativitás**: A kovarianciafüggvény mindig nemnegatív, azaz

$$cov(X, X) \ge 0$$

Ha a két változó független, akkor az egyenlőség akkor és csak akkor áll fenn, ha az $X$ állandó.

5. **Normálás**: Ha $X$ és $Y$ normális eloszlásúak, akkor a kovarianciafüggvény teljesen meghatározza a két változó közötti kapcsolatot.

6. **Két független változó kovarianciája nulla**: Ha $X$ és $Y$ független változók, akkor a kovarianciafüggvényük zérus:

$$cov(X, Y) = 0$$