---
tags: OE/ALKMAT/Sztocha 
aliases: ["Brown mozgás","wiener", "wiener folyamat", "wiener folyamatra"]
---
# wiener folyamat
Akkor nevezünk egy folyamatot Wiener folyamatnak ($W(t), t\ge 0$), ha következő tulajdonságokat teljesítik
- független növekményű [[Gauss-folyamat|Gauss folyamat]]
- Trajektóriái 1 valószínűséggel folytonosak
- $W(0) = 0$
- [[várható érték|Várható értéke]] 0, minden $t$-re
- $VAR(W(t)) = \sigma^2 * t$
- $t$ időváltozó, $t \ge 0$
#Szeidl/sztochajegyzet 
# standard wiener folyamat
Amennyiben a Wiener folyamat teljesíti, hogy $\sigma = 1$ akkor azt standard Wiener folyamatnak nevezzük.
#Szeidl/sztochajegyzet

# wiener folyamat tulajdonságai
- $$COV(W(t), W(s)) = \min(s,t)$$
	- $t,s \ge 0$ ezek egymástól független időpontokat jelölnek a Wiener folyamat útján
- $$VAR(W(t)-W(s))=|t-s|$$
	- $t,s \ge 0$ ezek egymástól független időpontokat jelölnek a Wiener folyamat útján
- $\overline{W}(t) = -W(t)$ is Wiener-folyamat
	- $t \ge 0$
- $\overline{W}(t) = W(t+s_0) - W(s_0)$ is Wiener-folyamat, amely nem függ $W_s, 0 \le s \le s_0$ folyamattól
	- $t \ge 0$
- $cW(t/c^2)$ Wiener folyamat
	- $c > 0$ valamilyen konstans
	- $t \ge 0$ időváltozó
	- automodalitásnak nevezzük
- Rendelkezik Markov tulajdonsággal
	- aktuális állapota azonnal meghatározza annak jövőbeni állapotát
	- nincs memóriája az előző állapotokról
#Szeidl/sztochajegyzet 
- $\lim_{t \to \infty} \dfrac{W_t}{t}=0$ [[nagy számok erős törvénye]] szerint, 1 valószínűséggel
- Sehol sem differenciálható
#Ludwig/Szotchasztikus_differenciál 
## Standard-wiener folyamat plusz tulajdonságai
- Standard Wiener folyamat véges dimenziós eloszlásainak sűrűségfüggvénye: $$\begin{aligned}
f(y_1, \dots, y_m; t_1, \dots , t_n) &= (2\pi)^{-n/2}\left(t_1*\prod_{k=2}^n(t_n-t_{n-1}) \right)^{1/2} \cdot \\
&\cdot e^{-\cfrac{1}{2} \left( \cfrac{y_1^2}{t_1}+\sum_{k=2}^n \cfrac{(y_n-y_{n-1})^2}{t_n - t_{n-1}} \right)}
\end{aligned}$$
	- $0 < t_1 < t_2 < \dots < t_n \infty$
	- $y_1, \dots, y_n \in \mathbb{R}$ 
#Szeidl/sztochajegyzet 
- [[iterált logaritmus tétel|iterált logaritmus tételből]] következik, hogy:
	- $\limsup_{t \to \infty} \dfrac{W_t}{\sqrt[2]{2*t*\ln(\ln(t))}}=1$
	- $\liminf_{t \to \infty} \dfrac{W_t}{\sqrt[2]{2*t*\ln(\ln(t))}}=-1$
	- ezek leírják a Wiener folyamat aszimptotikus viselkedését
	- létezik olyan $t_0$ időpont, amelytől igaz, hogy: $-(1+ \epsilon)*\sqrt[2]{2*t*\ln(\ln(t))} \le W_t \le (1+ \epsilon)*\sqrt[2]{2*\ln(\ln(t))}$
		- $\epsilon > 0$
#Ludwig/Szotchasztikus_differenciál 
# Wiener-folyamat konstrukciója
A Wiener folyamat konstrukciójának általános alakja:
$$W(t) = \sum_{k=0}^{\infty}X_k \int_0^t \phi_k (u) du$$
- $t$ az idő változó
	- $t$-t elegendő $[0,1]$ intervallumon megadni, mert független növekményű [[Gauss-folyamat|Gauss folyamatról]] van szó 
- $X_k \sim N(0,1)$
- $\phi$ ortonormált bázis a $\mathcal{L}^2[0,1]$ [[L2 függvénytér|L2 függvénytéren]]
#Szeidl/sztochajegyzet 
## Wiener-féle konstrukció
Egy másik konstrukciója a Wiener folyamatnak a Wiener-féle konstrukció:
$$W(t) = \cfrac{t}{\sqrt{\pi}} X_0 + \sqrt{2} \sum_{n=1}^\infty \sum_{k = 2^{n-1}}^{2^n-1}\sqrt{\cfrac{2}{\pi}}\cfrac{sin(k*t)}{k} X_k$$
- $t$ időváltozó
- $X_k$ a $k.$ időpontban lévő [[Sztochasztikus folyamatok|sztochasztikus folyamat]]

#Szeidl/sztochajegyzet 
## Lévy-Ciesielski féle konstrukció
$$W(t) = S_0(t)X_0 + \sum_{n=1}^{\infty} \sum_{k \text{ (páratlan) }=1 }^{2^{n}}S_{k2^{-n}}(t)X_{k2^{-n}}$$
- Ahol $S_k(t)$-t Schauder-függvények: $$S_k(t) = \int_{0}^t h_k(u)du$$
	- És $h_k$ pedig Haar-függvényt jelent: $$\begin{aligned}
	 h_0(x) & \equiv 1 \\
	 h_{k 2^{-n}}(x) & = \begin{cases}
		 +2^{(n-1)/2}, & (k-1)2^{-n} \le x < k2^{-n}, \\
		 -2^{(n-1)/2}, & k2^{-n} \le x < (k+1)2^{-n}, \\
		 0 & \text{egyébként}
	 \end{cases}
 \end{aligned}$$
- $X \sim N(0,1)$
#Szeidl/sztochajegyzet 

# [[Fehérzaj folyamat|fehérzaj]] [[spektrális sűrűségfüggvény|spektrális sűrűségfüggvénye]]
![[Pasted image 20230403205914.png]]
#Szeidl/sztochajegyzet 