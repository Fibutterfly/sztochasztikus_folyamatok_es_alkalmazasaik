---
tags: OE/ALKMAT/Sztocha 
aliases: ["stacionárius", "autó-kovariancia fügvény", "stacionárius folyamat"]
---

# tágabb értelemben stacionárius
Ha egy [[Sztochasztikus folyamatok|sztochasztikus folyamat]] tágabb értelemben stacionárius, az azt jelenti, hogy a [[várható érték|várható értéke]] és a [[kovariancia]] függvénye csak az időbeli különbségtől függ, és nem az abszolút időponttól.
#chatGPT 

# tágabb értelemben stacionárius eloszlásainak feltételei
Adott a következő véges dimenziós rendszer:
$$\begin{aligned}
	P(X_t \le x) &= F_t(x) \\
	P(X_{t_1} \le x_t, X_{t_2} \le x_2) &=F_{t_1,t_2}(x_1,x_2) \\
	\vdots \\
	P(X_{t_1} \le x_1 , \dots, X_{t_n} \le x_n) &= F_{t_1, \dots, t_n}=F(x_1, \dots, x_n)
	\vdots
\end{aligned}$$
amely eleget tesz:
- [[szimmetriafeltétel|szimmetriafeltételnek]]
- [[kompatibilitási feltétel|kompatibilitási feltételnek]]
#Ludwig/Szotchasztikus_differenciál
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
- [[Autoregresszív modell (AR)|autoregresszív]]
- [[mozgóátlag modell (MA)|mozgóátlag]]
- ARMA
- ARIMA

# [[Spektrális sűrűségfüggvény]] segítségével lévő stacionárius folyamat előállítása
$$X_t = \mu_X + \int_{- \pi} ^\pi e^{it\lambda} d Z(\lambda)$$
$$X_t = \mu_X + \sum_{k=-\infty}^{\infty}Z_ke^{i*t*\lambda_k}$$
- $\mu_X$ a [[várható érték]]
- $t$ az idő változó
- $Z(\lambda), -\pi \le \lambda \le \pi$ egy [[Sztochasztikus folyamatok|sztochasztikus folyamat]], amely zérus [[várható érték|várható értékű]]
- $E(Z(\lambda^{\prime\prime} - Z(\lambda^{\prime}))^2 = G_X(\lambda^{\prime \prime}) -G_X(\lambda^{\prime})$, ha $-\pi \le \lambda^{\prime} < \lambda^{\prime \prime} \le \pi$ 