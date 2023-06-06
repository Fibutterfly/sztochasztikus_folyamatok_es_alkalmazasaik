---
tags: OE/ALKMAT/Sztocha 
aliases: ["várható értékű", "várható értéke", "várható értékei"]
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

# Várható érték becslése
Legyen a várható érték becslése:
$$\bar{X} = \cfrac{1}{T} \sum_{i = 1}^{T}X_i$$
- $T$ az összes idő megfigyelése
- $X$ a [[Sztochasztikus folyamatok|sztochasztikus folyamat]].
Mint minden más statisztikai becsléstől ettől is elvárjuk a torzítatlanságot.
## Torzítatlansága a várható érték becslésének
$$E(\bar{X}) = \cfrac{1}{T} \sum_{i = 1}^{T}X_i = \cfrac{1}{T} \sum_{i=1}^T \mu_X = \mu_X$$
Így látszódik, hogy torzítatlan.