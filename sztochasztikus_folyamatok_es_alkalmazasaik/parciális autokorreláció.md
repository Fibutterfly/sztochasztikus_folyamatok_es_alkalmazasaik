---
tags: OE/ALKMAT/Sztocha 
aliases: [""]
---
# parciális [[autokorrelációs függvény|autokorreláció]]
$Z_1, \dots, Z_k$ [[valószínűségi változó|valószínűségi változók]] melletti parciális korrelációnak nevezzük a következő összefüggést:
$$\rho = CORR(X - \hat{X}, Y - \hat{Y}) = \cfrac{COV(X-\hat{X}, Y - \hat{Y})}{D(X - \hat{X})D(Y - \hat{Y})}$$
Ahol:
- $X,Y,Z$ [[valószínűségi változó|valószínűségi változók]]
- $\hat{X} = \hat{X}(Z_1, \dots, Z_k), \hat{Y} = \hat{Y}(Z_1, \dots, Z_k)$
- $D(X - \hat{X}) > 0, D(Y - \hat{Y}) > 0$.

Megmutatja az $X$ és $Y$ közötti kapcsolat erősségét azután, hogy mindkét változóban kiküszöböltük a $Z$ [[valószínűségi változó|valószínűségi változók]] hatását.

# parciális [[autokorrelációs függvény|autokorreláció]] [[tágabb értelemben stacionárius|stacionárius folyamat]] esetén
Azt mutatja meg, hogy két időbeli pontra vonatkozó [[kovariancia|korreláció]] mennyiben magyarázható a közöttük lévő időbeli pontok hatásának kiküszöbölésével. [[tágabb értelemben stacionárius|Stacionárius]] folyamatok esetén a parciális [[autokorrelációs függvény|autokorreláció]] különösen fontos, mivel lehetővé teszi számunkra, hogy azonosítsuk a folyamat autoregresszív (AR) modellének paramétereit.
$X_t$ és $X_{t-k}$ közötti parciális [[autokorrelációs függvény|autokorreláció]] alatt a következő összefüggést értjük:
$$\rho_k = CORR(X_t - \widehat{X}_t, X_{t-k} - \widehat{X}_{t}) = \cfrac{COV(X_t - \widehat{X}_t, X_{t-k} - \widehat{X}_{t})}{D(X_t - \widehat{X}_t)D(X_{t-k} - \widehat{X}_{t})}$$
- $k \in \mathbb{Z}$ 
- $\widehat{X}_t = \widehat{X}_t(X_{t-1}, \dots, X_{t-k+1})$
- $D(X_t - \hat{X}_t) > 0, D(X_{t-k} - \hat{X}_t) > 0$.
#Szeidl/sztochajegyzet 