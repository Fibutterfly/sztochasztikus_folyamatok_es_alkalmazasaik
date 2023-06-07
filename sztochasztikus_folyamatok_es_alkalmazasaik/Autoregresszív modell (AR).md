---
tags: OE/ALKMAT/Sztocha OE/ALKMAT/Sztocha/4tétel 
aliases: ["Autoregresszív", "AR", "Autoregresszív modell"]
TARGET DECK: 02::Sztocha
---
# Autoregresszív [[modell]] (AR)
A p-edrendű autoregresszív modellnek a következőt hívjuk:
$$x_t = \sum_{k=1}^{p}(c_k x_{t-k}) + \epsilon_t$$
Ahol:
- $x_t$ a $t.$ időpontban lévő véletlen [[tágabb értelemben stacionárius|stacionárius folyamat]] értéke
- $c_i$ a $t-i.$ időponthoz tartozó [[autoregressziós együttható]]
- $p$ az autoregressziós [[modell]] rendje
- $\epsilon_t$ a $t.$ időponthoz tartozó diszkrét idejű [[Fehérzaj folyamat|fehérzaj]].

# AR folyamat rangjának meghatározása
$$\rho_k = \dfrac{|R^*_k|}{|R_k|}$$
- $\rho_k$ egy arány, amelyet $k$-adik lépésben definiálunk, fontos információ az AR folyamat rendjének meghatározása
- $R_k$ a [[Yule-Walker egyenletrendszer]] autokorrelációs mátrixa
- $R^*_K$ mátrixot úgy kapjuk, hogy a $k.$ oszlopot a $[\gamma(1), \gamma(2), \dots, \gamma(k)]^T$ vektorral helyettesítjük
- $\gamma(k) = \dfrac{R_X(k)}{R_X(0)}$, normált [[autokorrelációs függvény|autokorreláció]]-függvény

#Szeidl/sztochajegyzet 


# AR karakterisztikus polinomja
$$P(x) = x_t - \sum_{k=1}^p c_k*X(t-k)$$
- $P(e^{i*\lambda})$ -t nevezzük az AR [[suli/02 ALKMAT/sztochasztikus_folyamatok_es_alkalmazasaik/karakterisztikus függvény|karakterisztikus polinomjának]]
	- $P(e^{i*\lambda})=1-c*e^{i*\lambda}$
- $X_t$ [[Sztochasztikus folyamatok|sztochasztikus folyamat]]
- $p$ az autoregresszív [[modell]] szintje
- $a_k$ az [[autoregressziós együttható]]

#Budai/Idősorok_osztályozása
# AR [[spektrális sűrűségfüggvény|spektruma]]
$$g_X(\lambda) = \dfrac{\sigma^2_\epsilon}{2*\pi} * \dfrac{1}{|P(e^{i*\lambda})|^2}= \dfrac{\sigma^2_\epsilon}{2*\pi} * \dfrac{1}{|1- c*e^{i*\lambda}|^2}$$
Ahol:
- $g_X$ az $X$ sztochasztikus folyamathoz tartozó AR függvény [[spektrális sűrűségfüggvény|spektrális sűrűségfüggvénye]]
- $\sigma^2_\epsilon$ az $\epsilon$ [[Fehérzaj folyamat|fehérzajhoz]] tartozó szórás négyzet
- $P(e^{i*\lambda})$ az AR karakterisztikus polinomja
- $c$ az [[autoregressziós együttható]]

#Budai/Idősorok_osztályozása 

# AR autokorrelációs függvénye
$$\begin{align}
	&x_{t - \lambda}*x_t &&= \sum_{k=1}^p c_p*x_{t-\lambda}*x_{t-k} \tag{ARAkF.1} \\
	&R_k &&= \sum_{i=1}^p c_i*R_{k-i} \tag{ARAkF.2}
\end{align}$$
- felírjuk (1)-es módban
- tagonként várható értéket képzünk
- $c$ [[autoregressziós együttható]]
- $R_k$ [[autokorrelációs függvény|autokorreláció]]
- $x_t$ $t$ időpontban lévő realizációja a [[tágabb értelemben stacionárius|stacionárius]] folyamatnak

#Michelberger/alkalmazott_folyamatstatisztika 

# Kártyák
START
Basic
Front:
AR autokorrelációs függvénye
Back:
$$\begin{align}
	&x_{t - \lambda}*x_t &&= \sum_{k=1}^p c_p*x_{t-\lambda}*x_{t-k} \tag{ARAkF.1} \\
	&R_k &&= \sum_{i=1}^p c_i*R_{k-i} \tag{ARAkF.2}
\end{align}$$
- felírjuk (1)-es módban
- tagonként várható értéket képzünk
- $c$ [[autoregressziós együttható]]
- $R_k$ [[autokorrelációs függvény|autokorreláció]]
- $x_t$ $t$ időpontban lévő realizációja a [[tágabb értelemben stacionárius|stacionárius]] folyamatnak
<!--ID: 1686168908063-->
END

START
Basic
Front:
AR spektruma
Back:
$$g_X(\lambda) = \dfrac{\sigma^2_\epsilon}{2*\pi} * \dfrac{1}{|P(e^{i*\lambda})|^2}= \dfrac{\sigma^2_\epsilon}{2*\pi} * \dfrac{1}{|1- c*e^{i*\lambda}|^2}$$
Ahol:
- $g_X$ az $X$ sztochasztikus folyamathoz tartozó AR függvény [[spektrális sűrűségfüggvény|spektrális sűrűségfüggvénye]]
- $\sigma^2_\epsilon$ az $\epsilon$ [[Fehérzaj folyamat|fehérzajhoz]] tartozó szórás négyzet
- $P(e^{i*\lambda})$ az AR karakterisztikus polinomja
- $c$ az [[autoregressziós együttható]]
<!--ID: 1686168908070-->
END