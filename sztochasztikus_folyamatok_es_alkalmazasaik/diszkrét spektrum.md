---
tags: OE/ALKMAT/Sztocha OE/ALKMAT/Sztocha/3tétel OE/ALKMAT/Sztocha/7tétel 
aliases:
TARGET DECK: 02::Sztocha
---

# Diszkrét [[spektrális sűrűségfüggvény]]
$$\begin{align}
	R_X(j) = \sum_{m=-\infty}^\infty \sigma_m^2 *e^{i*j *\lambda_m} \tag{DSSf.1}
\end{align}$$
- $R_X$ [[kovarianciafüggvény]]
- $j = t-s$
- $\sigma^2$ variancia
- $\lambda$ frekvencia változás

#Szeidl/sztochajegyzet 

# Diszkrét [[spektrális sűrűségfüggvény]] speciális tulajdonsága
Ha $\sum_{k=- \infty}^{\infty}|R_X(u)| < \infty$ feltétel teljesül, akkor a [[spektrális sűrűségfüggvény]] közvetlenül is előállítható:
$$g_X(\lambda) = \cfrac{1}{2 \pi} \sum_{k = - \infty} ^{\infty} R_X(k) e^{-i * k *\lambda}$$
Ez tovább írható:
$$
\begin{aligned}
	g_X(\lambda) =& \cfrac{1}{ 2  \pi} \sum_{k = - \infty}^{\infty}R_X(k)cos(k \lambda) = \\
	=& \cfrac{1}{2 \pi} \left( \sigma_X^2 + 2 \sum_{k = 1}^{\infty} R_X(k) cos(k \lambda) \right)
\end{aligned}$$
#Szeidl/sztochajegyzet 

# Diszkrét [[spektrális sűrűségfüggvény|spektrum]] becslése
$$\begin{align}
	&X_t = \sum_{j=1}^q \left[ A_j* \cos(\lambda_j*t) + B_j* \sin(\lambda_j*t) \right] + \epsilon_t \tag{DSB.1} \\
	&A_j = a_j * \cos(\lambda_j) \tag{DBS.2} \\
	&B_j = - a_j* \sin(\lambda_j) \tag{DBS.3}
\end{align}$$
- $\lambda$ frekvencia változó
- $X_t$ [[harmonikus folyamat|véletlen koszinuszfolyamat]]
- $a_j$ súly
- súlyt és a frekvencia változót legkisebb négyzetek módszerével keressük

#Szeidl/sztochajegyzet 
# kártyák
START
Basic
Front:
Diszkrét [[spektrális sűrűségfüggvény]]
Back:
$$\begin{align}
	R_X(j) = \sum_{m=-\infty}^\infty \sigma_m^2 *e^{i*j *\lambda_m} \tag{DSSf.1}
\end{align}$$
- $R_X$ [[kovarianciafüggvény]]
- $j = t-s$
- $\sigma^2$ variancia
- $\lambda$ frekvencia változás
<!--ID: 1686165256542-->
END

START
Basic
Front:
Diszkrét spektrális sűrűségfüggvény speciális speciális tulajdonsága
Back:
Ha $\sum_{k=- \infty}^{\infty}|R_X(u)| < \infty$ feltétel teljesül, akkor a [[spektrális sűrűségfüggvény]] közvetlenül is előállítható:
$$g_X(\lambda) = \cfrac{1}{2 \pi} \sum_{k = - \infty} ^{\infty} R_X(k) e^{-i * k *\lambda}$$
Ez tovább írható:
$$
\begin{aligned}
	g_X(\lambda) =& \cfrac{1}{ 2  \pi} \sum_{k = - \infty}^{\infty}R_X(k)cos(k \lambda) = \\
	=& \cfrac{1}{2 \pi} \left( \sigma_X^2 + 2 \sum_{k = 1}^{\infty} R_X(k) cos(k \lambda) \right)
\end{aligned}$$
<!--ID: 1686165256551-->
END

START
Basic
Front:
Diszkrét Spektrum becslése
Back:
$$\begin{align}
	&X_t = \sum_{j=1}^q \left[ A_j* \cos(\lambda_j*t) + B_j* \sin(\lambda_j*t) \right] + \epsilon_t \tag{DSB.1} \\
	&A_j = a_j * \cos(\lambda_j) \tag{DBS.2} \\
	&B_j = - a_j* \sin(\lambda_j) \tag{DBS.3}
\end{align}$$
- $\lambda$ frekvencia változó
- $X_t$ [[harmonikus folyamat|véletlen koszinuszfolyamat]]
- $a_j$ súly
- súlyt és a frekvencia változót legkisebb négyzetek módszerével keressük
<!--ID: 1686251428037-->
END