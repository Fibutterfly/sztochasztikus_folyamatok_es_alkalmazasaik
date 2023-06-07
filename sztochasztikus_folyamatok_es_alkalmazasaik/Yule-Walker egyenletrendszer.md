---
tags: OE/ALKMAT/Sztocha OE/ALKMAT/Sztocha/4tétel 
aliases: ["Yule-Walker", "Yule-Walker egyenletek", "Yule-Walker egyenlet"]
TARGET DECK: 02::Sztocha
---
# Yule-Walker egyenletrendszer
A Yule-Walker egyenletrendszer az [[Autoregresszív modell (AR)|autoregresszív modell]] paramétereinek becslésére használt lineáris egyenletekből álló rendszer, ami a következő formában van:
$$\gamma = R_p * c$$
- $\gamma$ az [[autokorrelációs függvény]] a $k.$ értékeit tartalmazza $$\gamma = \left[ \begin{array}{c}
\gamma_1 \\ \gamma_2 \\ \vdots \\ \gamma_p
\end{array}\right]$$
- $R_p$ szintén az [[autokorrelációs függvény]] $k.$ értékeit tartalmazza egy kicsit másmilyen formátumban. $$R_p = \left[\begin{array}{c}
\gamma(0) & \gamma(1) & \gamma(2) & \dots & \gamma(p-1) \\
\gamma(1) & \gamma(0) & \gamma(1) & \dots & \gamma(p-2) \\
\gamma(2) & \gamma(1) & \gamma(0) & \dots & \gamma(p-3) \\
\vdots & \vdots & \vdots & \ddots & \vdots \\
\gamma(p-1) & \gamma(p-2) & \gamma(p-3) & \dots & \gamma(0)
\end{array}\right]$$
	- $\gamma(0)$ általában $1$
	- $\gamma(k) = \dfrac{R_X(k)}{R_X(0)}$, normált [[autokorrelációs függvény|autokorreláció]]-függvény
- $c$ az [[autoregressziós együttható|autoregressziós együtthatók]], ezeket szeretnénk becsülni. $$c = \left[\begin{array}{c}
c_1 \\ c_2 \\ \vdots \\ c_p
\end{array}\right]$$
#Szeidl/sztochajegyzet 

# Kártya
START
Basic
Front:
Yule-Walker egyenletrendszer
Back:
A Yule-Walker egyenletrendszer az [[Autoregresszív modell (AR)|autoregresszív modell]] paramétereinek becslésére használt lineáris egyenletekből álló rendszer, ami a következő formában van:
$$\gamma = R_p * c$$
- $\gamma$ az [[autokorrelációs függvény]] a $k.$ értékeit tartalmazza $$\gamma = \left[ \begin{array}{c}
\gamma_1 \\ \gamma_2 \\ \vdots \\ \gamma_p
\end{array}\right]$$
- $R_p$ szintén az [[autokorrelációs függvény]] $k.$ értékeit tartalmazza egy kicsit másmilyen formátumban. $$R_p = \left[\begin{array}{c}
\gamma(0) & \gamma(1) & \gamma(2) & \dots & \gamma(p-1) \\
\gamma(1) & \gamma(0) & \gamma(1) & \dots & \gamma(p-2) \\
\gamma(2) & \gamma(1) & \gamma(0) & \dots & \gamma(p-3) \\
\vdots & \vdots & \vdots & \ddots & \vdots \\
\gamma(p-1) & \gamma(p-2) & \gamma(p-3) & \dots & \gamma(0)
\end{array}\right]$$
	- $\gamma(0)$ általában $1$
	- $\gamma(k) = \dfrac{R_X(k)}{R_X(0)}$, normált [[autokorrelációs függvény|autokorreláció]]-függvény
- $c$ az [[autoregressziós együttható|autoregressziós együtthatók]], ezeket szeretnénk becsülni. $$c = \left[\begin{array}{c}
c_1 \\ c_2 \\ \vdots \\ c_p
\end{array}\right]$$
<!--ID: 1686170378537-->
END