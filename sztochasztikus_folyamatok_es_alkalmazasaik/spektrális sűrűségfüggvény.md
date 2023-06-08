---
tags: OE/ALKMAT/Sztocha OE/ALKMAT/Sztocha/3tétel OE/ALKMAT/Sztocha/5tétel OE/ALKMAT/Sztocha/7tétel OE/ALKMAT/Sztocha/fontos_fogalom 
aliases: ["spektrális sűrűségfüggvénye", "spektrum", "spektruma","spektrális sűrűségfüggvényére", "spektrumára", "spektrumának"]
TARGET DECK: 02::Sztocha
---
# spektrális sűrűségfüggvény
A [[Herglotz-tétel]] szerint, a kovarianciafüggvényt kitudjuk fejezni a következő képen:

$$R_X (u)=\int_{-\pi}^\pi e^{i*\lambdaű*u}*g_X(\lambda)d\lambda$$

Ebben az összefüggésben a spektrális sűrűségfüggvény a $g_X(\lambda)$.
#Szeidl/sztochajegyzet 

# folytonos spektrum konzisztens becslése 
$$\begin{align}
	\widehat{g}_T(\lambda) = \dfrac{1}{2* \pi} \sum_{j = 1-T}^{T- |k|} \kappa \left( \dfrac{|j|}{K_T} \right)*\overline{R}_{1j}*e^{i*j*\lambda} \tag{FSKB.1}
\end{align}$$
- $\lambda$ frekvencia változó
- $T$ az ablakméretet jelöli
- $k$ valamilyen konstans
- $0 \le k \le T - 1$
- $\kappa$ kernel függvény
- $K$ kernelező konstans
- $\overline{R}_{1k} = \overline{R}_{1-k} = \dfrac{1}{T-k}*\sum_{j=1}^{T-k} X_j*X_{j+k}$ a [[kovarianciafüggvény]] becslése
- [[legkisebb négyzetek módszere]]

#Szeidl/sztochajegyzet 
# kártyák
START
Basic
Front:
folytonos spektrális sűrűségfüggvény
Back:
A [[Herglotz-tétel]] szerint, a kovarianciafüggvényt kitudjuk fejezni a következő képen:

$$R_X (u)=\int_{-\pi}^\pi e^{i*\lambdaű*u}*g_X(\lambda)d\lambda$$

Ebben az összefüggésben a spektrális sűrűségfüggvény a $g_X(\lambda)$.
<!--ID: 1686165403711-->
END

START
Basic
Front:
folytonos spektrum konzisztens becslése 
Back:
$$\begin{align}
	\widehat{g}_T(\lambda) = \dfrac{1}{2* \pi} \sum_{j = 1-T}^{T- |k|} \kappa \left( \dfrac{|j|}{K_T} \right)*\overline{R}_{1j}*e^{i*j*\lambda} \tag{FSKB.1}
\end{align}$$
- $\lambda$ frekvencia változó
- $T$ az ablakméretet jelöli
- $k$ valamilyen konstans
- $0 \le k \le T - 1$
- $\kappa$ kernel függvény
- $K$ kernelező konstans
- $\overline{R}_{1k} = \overline{R}_{1-k} = \dfrac{1}{T-k}*\sum_{j=1}^{T-k} X_j*X_{j+k}$ a [[kovarianciafüggvény]] becslése
- [[legkisebb négyzetek módszere]]
<!--ID: 1686253978263-->
END