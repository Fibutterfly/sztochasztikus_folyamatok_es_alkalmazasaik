---
tags: OE/ALKMAT/Sztocha 
aliases:
---

# Ito-féle sztochasztikus integrál
$$\lim_{n \to \infty}\sum_{k=1}^{n} f(z_{k-1})[W(z_k)- W(z_{k-1})] = \int_{a}^b f(s) dW(s)$$
- eredménye: 0 [[várható érték|várható értékű]]  normális eloszlású [[valószínűségi változó]]
- $\Delta W(z_k) = W(z_{k+1}) - W(z_k) \sim N(0, \Delta t)$
- $f(z_{k-1})$ egy ismert szám, ezt szorozzuk a $\Delta W(z_k)$-val
- rendelkezik a [[Stielejtes integrál]] tulajdonságaival
#Száz/num3

# Ito-féle sztochasztikus integrál tulajdonságai
- Az $f$ függvény $dW$ szerinti integráljának [[várható érték|várható értéke]] $0$
- Az integrál négyzetének [[várható érték|várható értéke]] megegyezik az $f$ függvény négyzetének Riemann integráljával
- $W(t)$-nek egy pontja sem differenciálható

#Száz/num3