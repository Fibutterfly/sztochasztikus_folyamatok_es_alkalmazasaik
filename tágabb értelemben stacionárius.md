---
tags: OE/ALKMAT/Sztocha 
aliases: ["stacionárius", "autó-kovariancia fügvény", "stacionárius folyamat"]
---

# tágabb értelemben stacionárius
Ha egy [[Sztochasztikus folyamatok|sztochasztikus folyamat]] tágabb értelemben stacionárius, az azt jelenti, hogy a várható értéke és a [[kovariancia]] függvénye csak az időbeli különbségtől függ, és nem az abszolút időponttól.
#chatGPT 


# Tágabb értelemben stacionárius
Amennyiben a következő feltételek megegyeznek az egy tágabb értelemben vett [[tágabb értelemben stacionárius|stacionárius]] folyamat:
- $\mu_X (t) = E(X_t)$
- $R_X(s,t) = cov(X_s, X_t) = E(X_t - \mu_X (t)) (X_s - \mu_X (s))$
Ahol a következők a következőket jelenti:
- $t, s \in \mathcal{T}$, tehát időbéli változók
- $\mu_X (t)$ egy konstans, ami csak az időtől függ és megegyezik a várható értékkel
- $R_X$ a [[kovariancia]] függvény
- $E(X_t^2) < \infty$ 
#Szeidl/sztochajegyzet 
# [[időben diszkrét folyamatok]] elemzéseire használt modellek
- autoregresszív
- mozgóátlag
- ARMA
- ARIMA

# [[Spektrális sűrűségfüggvény]] segítségével lévő stacionárius folyamat előállítása
$$X_t = \mu_X + \int_{- \pi} ^\pi e^{it\lambda} d Z(\lambda)$$
$$X_t = \mu_X + \sum_{k=-\infty}^{\infty}Z_ke^{i*t*\lambda_k}$$
- $\mu_X$ a [[várható érték]]
- $t$ az idő változó
- $Z(\lambda), -\pi \le \lambda \le \pi$ egy [[Sztochasztikus folyamatok|sztochasztikus folyamat]], amely zérus [[várható érték|várható értékű]]
- $E(Z(\lambda^{\prime\prime} - Z(\lambda^{\prime}))^2 = G_X(\lambda^{\prime \prime}) -G_X(\lambda^{\prime})$, ha $-\pi \le \lambda^{\prime} < \lambda^{\prime \prime} \le \pi$ 