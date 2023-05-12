---
tags: OE/ALKMAT/Sztocha 
aliases: ["Doob-Meyer tételnek"]
---
# Doob-Meyer tétel
$${st.\lim_{n \to \infty}} \int_{t_0}^t | G(s) - G_n(s)|^2ds = 0$$
ahol:
- ${st. \lim}$ azt jelenti, hogy sztochasztikus középben vett határértéke
- $G, G_n \in M_2[t_0,t]$ lépcsős függvények.

Amennyiben igaz, hogy $\int_{t_0}^t G_n(s) dW_s$ által van definiálva az érték, akkor igaz az is, hogy
$${st. \lim_{n \to \infty}} \int_{t_0}^t G_n(s) dW_s = I(G)$$
ahol: $I(G)$ a $\{G_n\}$ sorozat megválasztásától független [[valószínűségi változó]].