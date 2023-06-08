---
tags: OE/ALKMAT/Sztocha OE/ALKMAT/Sztocha/fontos_fogalom 
aliases: ["autokorrelációs függvényt", "autokorreláció"]
TARGET DECK: 02::Sztocha
---
# autokorrelációs függvény
Megmutatja, hogy a folyamat időbeli részei mennyire hasonlítanak egymáshoz, mennyire van közös mozgásuk.
Legyen $X_t$ [[tágabb értelemben stacionárius|stacionárius]] folyamat $R_X(t)$ pedig [[kovarianciafüggvény]], ekkor az autokorrelációs függvényt a következő képen értelmezzük:
$$r_X(t) = \dfrac{1}{R_X(0)}R_X(t) = \cfrac{1}{\sigma_X^2}R_X(t)$$.
#Szeidl/sztochajegyzet 

# autokorrelációs függvény [[spektrális sűrűségfüggvény|spektruma]]
A következőt nevezzük az autokorrelációs függvény [[spektrális sűrűségfüggvény|spektrumának]]:
$$g_X(\lambda) = \cfrac{1}{2 \pi} \sum_{k = - \infty} ^{\infty} r_X(k) e^{-i * k *\lambda}$$
$$r_X(k) = \dfrac{1}{R_X(0)}*R_X(k) = \dfrac{1}{\sigma^2_X}*R_X(k)$$
A zaj, az interferencia vagy a periodikus mintázatok kezelésében. A [[spektrális sűrűségfüggvény|spektrum]] azonban csak egy részleges képet ad a folyamatról, és egyedül nem elegendő a folyamat jellemzéséhez. Számos más jellemzőnek, mint például az autoregressziós [[modell]] paramétereinek, a szűrő paramétereinek vagy a spektrális sűrűségfüggvénynek ismerete szükséges lehet a folyamatok részletes elemzéséhez..

# kártyák
START
Basic
Front:
autokorrelációs függvény
Back:
Megmutatja, hogy a folyamat időbeli részei mennyire hasonlítanak egymáshoz, mennyire van közös mozgásuk.
Legyen $X_t$ [[tágabb értelemben stacionárius|stacionárius]] folyamat $R_X(t)$ pedig [[kovarianciafüggvény]], ekkor az autokorrelációs függvényt a következő képen értelmezzük:
$$r_X(t) = \dfrac{1}{R_X(0)}R_X(t) = \cfrac{1}{\sigma_X^2}R_X(t)$$.
<!--ID: 1686259421762-->
END