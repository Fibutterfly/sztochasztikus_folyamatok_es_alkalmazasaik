---
tags: OE/ALKMAT/Sztocha 
aliases:
---

# Sztochasztikus integrál
Legyen:
$$\int_{t_0}^t G(s,\omega) dW_s(\omega) $$
ahol:
- $t_0, t$ az intervallum amin értelmezzük az integrálást
- $G \in M_2^{d,m}[t_0,t]$ 
- $W_s(\omega)$ kifejezés egy adott $\omega$ minta esetén az $s$ időpillanatban mért [[standard wiener folyamat|Wiener]]-folyamat értékét jelöli.
- $s$ az időpillanat, amiben vizsgálódunk.

## lépései
1. megvizsgáljuk, hogy $G$ lépcsős függvény-e, tehát létezik-e olyan felbontás, amelyre igaz az, hogy $t_0 < t_1 < \dots < t_n = t$ és $G(s) = G(t_{t-1}) \forall s \in [t_{i-1},t_i[, i=1,\dots,n$, ennek tulajdonságai az [[Ito Lemma|Ito lemmában]] vannak leírva.
2. Megkeressük a $G_m$ sorozatot, amely eleget tesz a [[Wiener-Paley lemma|Wiener–Paley lemmának]]
3. Majd minden függvényt átalakítunk úgy, hogy eleget tegyen a [[Doob általánosított egyenlőtlensége|Doob általánosított egyenlőtlenségének]]
4. Ellenőrizzük, hogy eleget tesz-e a [[Doob-Meyer tétel|Doob-Meyer tételnek]]
5. elvégezzük rajta az [[Ito-féle sztochasztikus integrál|Ito-féle sztochasztikus integrálást]] 

#Ludwig/Szotchasztikus_differenciál 