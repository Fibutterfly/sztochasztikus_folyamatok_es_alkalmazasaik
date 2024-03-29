---
tags: OE/ALKMAT/Sztocha OE/ALKMAT/Sztocha/5tétel OE/ALKMAT/Sztocha/fontos_fogalom 
aliases: ["transzfer függvénynek", "transzferfüggvény"]
TARGET DECK: 02::Sztocha
---
# transzfer függvény
A [[szűrő koherenciafeltétel|szűrő koherenciafeltételhez]] tartozik az úgynevezett transzfer függvény:
$$H \left(e^{-i \lambda} \right) = \sum_{t = -\infty}^{\infty} e^{-i t \lambda} h(t)$$
- $H$ a transzfer függvény
- $\lambda$ az frekvencia tartományban lévő változások sebességét leíró paraméter.
Legyen $Y_t = L(X_t)$ [[tágabb értelemben stacionárius|stacionárius]] folyamat, ahol:
- $L$ egy [[lineáris szűrő]]
- $X_t$ egy [[tágabb értelemben stacionárius|stacionárius]] folyamat
Ekkor az $Y_t$ [[kovarianciafüggvény|kovarianciafüggvényére]] fennáll
$$R_Y(r,r+t) = R_Y(t)$$.
Ahol:
- $r$ a vizsgált időpont
- $t$ pedig, hogy mennyi időegységre van eltolva a vizsgálat vége az $r$-től
Az $Y_t$ [[spektrális sűrűségfüggvény|spektrális sűrűségfüggvényére]] pedig:
Több dimenziós esetben a
$$g_Y(\lambda) = H\left(e^{-i \lambda} \right)g_X(\lambda)H^{T*}\left(e^{-i \lambda} \right)$$
, egy dimenziós esetben pedig a
$$g_Y(\lambda) = g_X(\lambda)\left|H\left(e^{-i \lambda} \right)\right|^2$$
összefüggés igaz.
Ahol:
- $g$ a [[spektrális sűrűségfüggvény]]
- $\square^{T*}$ a transzponált, majd konjugált műveletek jelölik .

# kártya
START
Basic
Front:
Transzfer függvény
Back:
A [[szűrő koherenciafeltétel|szűrő koherenciafeltételhez]] tartozik az úgynevezett transzfer függvény:
$$H \left(e^{-i \lambda} \right) = \sum_{t = -\infty}^{\infty} e^{-i t \lambda} h(t)$$
- $H$ a transzfer függvény
- $\lambda$ az frekvencia tartományban lévő változások sebességét leíró paraméter.
Legyen $Y_t = L(X_t)$ [[tágabb értelemben stacionárius|stacionárius]] folyamat, ahol:
- $L$ egy [[lineáris szűrő]]
- $X_t$ egy [[tágabb értelemben stacionárius|stacionárius]] folyamat
Ekkor az $Y_t$ [[kovarianciafüggvény|kovarianciafüggvényére]] fennáll
$$R_Y(r,r+t) = R_Y(t)$$.
Ahol:
- $r$ a vizsgált időpont
- $t$ pedig, hogy mennyi időegységre van eltolva a vizsgálat vége az $r$-től
Az $Y_t$ [[spektrális sűrűségfüggvény|spektrális sűrűségfüggvényére]] pedig:
Több dimenziós esetben a
$$g_Y(\lambda) = H\left(e^{-i \lambda} \right)g_X(\lambda)H^{T*}\left(e^{-i \lambda} \right)$$
, egy dimenziós esetben pedig a
$$g_Y(\lambda) = g_X(\lambda)\left|H\left(e^{-i \lambda} \right)\right|^2$$
összefüggés igaz.
Ahol:
- $g$ a [[spektrális sűrűségfüggvény]]
- $\square^{T*}$ a transzponált, majd konjugált műveletek jelölik .
<!--ID: 1686242459212-->
END