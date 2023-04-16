---
tags: OE/ALKMAT/Sztocha 
aliases: ["autokorrelációs függvényt", "autokorreláció"]
---
# autokorrelációs függvény
Megmutatja, hogy a folyamat időbeli részei mennyire hasonlítanak egymáshoz, mennyire van közös mozgásuk.
Legyen $X_t$ [[tágabb értelemben stacionárius|stacionárius]] folyamat $R_X(t)$ pedig [[kovarianciafüggvény]], ekkor az autokorrelációs függvényt a következő képen értelmezzük:
$$r_X(t) = \dfrac{1}{R_X(0)}R_X(t) = \cfrac{1}{\sigma_X^2}R_X(t)$$.
#Szeidl/sztochajegyzet 

# autokorrelációs függvény [[spektrális sűrűségfüggvény|spektruma]]
A következőt nevezzük az autokorrelációs függvény [[spektrális sűrűségfüggvény|spektrumának]]:
$$g_X(\lambda) = \cfrac{1}{2 \pi} \sum_{k = - \infty} ^{\infty} r_X(k) e^{-i * k *\lambda}$$
A zaj, az interferencia vagy a periodikus mintázatok kezelésében. A [[spektrális sűrűségfüggvény|spektrum]] azonban csak egy részleges képet ad a folyamatról, és egyedül nem elegendő a folyamat jellemzéséhez. Számos más jellemzőnek, mint például az autoregressziós [[modell]] paramétereinek, a szűrő paramétereinek vagy a spektrális sűrűségfüggvénynek ismerete szükséges lehet a folyamatok részletes elemzéséhez..