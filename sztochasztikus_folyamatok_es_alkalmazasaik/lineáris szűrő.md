---
tags: OE/ALKMAT/Sztocha OE/ALKMAT/Sztocha/5tétel 
aliases: ["lineáris szűrők","lineáris transzformáció", "lineáris transzformációk", "lineáris operátor", "lineáris operátorok"]
TARGET DECK: 02::Sztocha
---
# lineáris szűrő
Lineáris szűrőt jelölje $L$

$$L(X_t) = \sum_{s = -\infty}^\infty h(t-s)X_s$$
- $X_t$ egy vagy több dimenziós [[tágabb értelemben stacionárius|stacionárius]] folyamat
	- Van a folyamatnak $R_x(u)$-val definiált kovarianciafüggvénye
	- $g_X(\lambda)$ [[spektrális sűrűségfüggvény|spektrum]] is létezik
	- $E(X_t) \equiv 0$
- $h(t)$ függvény eleget tesz a [[szűrő koherenciafeltétel|szűrő koherenciafeltételnek]] 
$$\sum_{u = -\infty} ^\infty \sum_{v = -\infty}^\infty h(u) R_X(v-u) h^T(v) < \infty$$

#Szeidl/sztochajegyzet 

# kártyák
START
Basic
Front:
Lineáris szűrő
Back:
Lineáris szűrőt jelölje $L$

$$L(X_t) = \sum_{s = -\infty}^\infty h(t-s)X_s$$
- $X_t$ egy vagy több dimenziós [[tágabb értelemben stacionárius|stacionárius]] folyamat
	- Van a folyamatnak $R_x(u)$-val definiált kovarianciafüggvénye
	- $g_X(\lambda)$ [[spektrális sűrűségfüggvény|spektrum]] is létezik
	- $E(X_t) \equiv 0$
- $h(t)$ függvény eleget tesz a [[szűrő koherenciafeltétel|szűrő koherenciafeltételnek]] 
$$\sum_{u = -\infty} ^\infty \sum_{v = -\infty}^\infty h(u) R_X(v-u) h^T(v) < \infty$$
<!--ID: 1686242423538-->
END