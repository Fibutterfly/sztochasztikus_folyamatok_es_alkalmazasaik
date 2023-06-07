---
tags: OE/ALKMAT/Sztocha OE/ALKMAT/Sztocha/2tétel OE/ALKMAT/Sztocha/3tétel 
aliases: ["stacionárius", "autó-kovariancia fügvény", "stacionárius folyamat"]
TARGET DECK: 02::Sztocha
---

# tágabb értelemben stacionárius
Ha egy [[Sztochasztikus folyamatok|sztochasztikus folyamat]] tágabb értelemben stacionárius, az azt jelenti, hogy a [[kovariancia]] függvénye csak az időbeli különbségtől függ, és nem az abszolút időponttól.
#chatGPT 

# Tágabb értelemben stacionárius tulajdonságok
Amennyiben a következő feltételek megegyeznek az egy tágabb értelemben vett [[tágabb értelemben stacionárius|stacionárius]] folyamat:
- $R_X(s,t) = cov(X_s, X_t) = E(X_t - \mu_X (t)) (X_s - \mu_X (s))$
- Második momentum létezik
Ahol a következők a következőket jelenti:
- $t, s \in \mathcal{T}$, tehát időbéli változók
- $\mu_X (t)$ egy konstans, ami csak az időtől függ és megegyezik a várható értékkel
- $R_X(k)$ a [[kovariancia]] függvény
- $E(X_t^2) < \infty$ 
#Szeidl/sztochajegyzet 
# [[időben diszkrét folyamatok]] elemzéseire használt modellek
- [[Autoregresszív modell (AR)|autoregresszív]]
- [[mozgóátlag modell (MA)|mozgóátlag]]
- ARMA
- ARIMA

# [[Spektrális sűrűségfüggvény]] segítségével lévő stacionárius folyamat előállítása
$$X_t = \mu_X + \int_{- \pi} ^\pi e^{it\lambda} d Z(\lambda)$$
$$X_t = \mu_X + \sum_{k=-\infty}^{\infty}Z_ke^{i*t*\lambda_k}$$
- $\mu_X$ a [[várható érték]]
- $t$ az idő változó
- $Z(\lambda), -\pi \le \lambda \le \pi$
	- [[Sztochasztikus folyamatok|sztochasztikus folyamat]]
	- zérus [[várható érték|várható értékű]]
	- korrelálatlan
- $E(Z(\lambda^{\prime\prime} - Z(\lambda^{\prime}))^2 = G_X(\lambda^{\prime \prime}) -G_X(\lambda^{\prime})$, ha $-\pi \le \lambda^{\prime} < \lambda^{\prime \prime} \le \pi$ 


# kártya
START
Basic
Front:
Tágabb értelemben stacionárius folyamat
Back:
Amennyiben a következő feltételek megegyeznek az egy tágabb értelemben vett [[tágabb értelemben stacionárius|stacionárius]] folyamat:
- $R_X(s,t) = cov(X_s, X_t) = E(X_t - \mu_X (t)) (X_s - \mu_X (s))$
- Második momentum létezik
Ahol a következők a következőket jelenti:
- $t, s \in \mathcal{T}$, tehát időbéli változók
- $\mu_X (t)$ egy konstans, ami csak az időtől függ és megegyezik a várható értékkel
- $R_X(k)$ a [[kovariancia]] függvény
- $E(X_t^2) < \infty$ 
<!--ID: 1686161588389-->
END

START
Basic
Front:
[[Spektrális sűrűségfüggvény]] segítségével lévő stacionárius folyamat előállítása
Back:

$$X_t = \mu_X + \int_{- \pi} ^\pi e^{it\lambda} d Z(\lambda)$$
$$X_t = \mu_X + \sum_{k=-\infty}^{\infty}Z_ke^{i*t*\lambda_k}$$
- $\mu_X$ a [[várható érték]]
- $t$ az idő változó
- $Z(\lambda), -\pi \le \lambda \le \pi$
	- [[Sztochasztikus folyamatok|sztochasztikus folyamat]]
	- zérus [[várható érték|várható értékű]]
	- korrelálatlan
- $E(Z(\lambda^{\prime\prime} - Z(\lambda^{\prime}))^2 = G_X(\lambda^{\prime \prime}) -G_X(\lambda^{\prime})$, ha $-\pi \le \lambda^{\prime} < \lambda^{\prime \prime} \le \pi$ 
<!--ID: 1686165893187-->
END