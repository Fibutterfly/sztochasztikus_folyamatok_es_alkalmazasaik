---
tags: OE/ALKMAT/Sztocha 
aliases: ["mozgóátlag", "mozgóátlag modell", "MA", "mozgóátlag-operátor", "mozgóátlag-modell"]
---
# mozgóátlag [[modell]] (MA)
A mozgóátlag modellnek a következőt szokás hívni:
$$X_t = \mu + \epsilon_t + \sum_{k = 1}^q d_k*\epsilon_{t-k}$$
Ahol:
-   $X_t$ az időpillanat $t$-beli megfigyelt érték
-   $\mu$ a [[várható érték]]
-   $\epsilon_t$ [[Fehérzaj folyamat|fehér zaj]]
- $d_k$ a mozgóátlag paraméterei, melyek meghatározzák a késleltetett [[Fehérzaj folyamat|fehér zaj]] lineáris kombinációját.

#chatGPT 

# Mozgóátlag [[modell]] [[spektrális sűrűségfüggvény|spektruma]]
$$g_X(\lambda) = \dfrac{\sigma^2_\epsilon}{2*\pi}*|Q(e^{i*\lambda})|^2$$
Ahol:
- $g$ a mozgóátlag [[spektrális sűrűségfüggvény|spektrális sűrűségfüggvénye]]
- $X$ [[Sztochasztikus folyamatok|sztochasztikus folyamat]]
- $\lambda$ frekvencia változó
- $\sigma^2_\epsilon$ a varianciája a [[Fehérzaj folyamat|fehérzajnak]]
- $Q(e^{i*\lambda})$ mozgóátlag [[modell]] karakterisztikus polinomja

#Budai/Idősorok_osztályozása 