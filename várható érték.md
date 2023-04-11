---
tags: OE/ALKMAT/Sztocha 
aliases: ["várható értékű"]
---
# várható érték feltétele
## diszkrét esetben
$$E(X) = \sum_{i=1}^{\infty}p_i |x_i| < \infty$$
## folytonos esetben
$$E(X) = \int_{-\infty}^{\infty}|x| f(x)dx < \infty$$

# Várható érték
Lényegében az első (centrális) momentum, egy funkciónál.
## Diszkrét esetben
$$E(X) = \sum_{i=1}^{\infty}p_i x_i$$
## Folytonos esetben
$$E(X) = \int_{-\infty}^{\infty}x f(x)dx$$
# várható érték tulajdonságai
- Ha $X$ az $1$ valószínűséggel [[korlátos]] [[valószínűségi változó]], akkor van olyan $x_1$ és $x_2$ konstans, hogy $P(x_1 \le X \le x_2)=1$ akkor $x_1 \le E(X) \le x_2$
- $E(cX)=cE(X)$
- $P(X=c) = 1 \to E(X)=c$
- $E(X+Y) = E(X) + E(Y)$
- $E(X*Y)=E(X)*E(Y)$