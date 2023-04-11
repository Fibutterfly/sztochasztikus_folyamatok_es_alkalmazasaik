---
tags: OE/ALKMAT/Sztocha 
aliases: ["spektrális sűrűségfüggvénye"]
---
# spektrális sűrűségfüggvény
A [[Herglotz-tétel]] szerint, a kovarianciafüggvényt kitudjuk fejezni a következő képen:

$$R_X (u)=\int_{-\infty}^\infty e^{i*\lambdaű*u}*g_X(\lambda)d\lambda$$

Ebben az összefüggésben a spektrális sűrűségfüggvény a $g_X(\lambda)$.
#Szeidl/sztochajegyzet 

# Spektrális sűrűségfüggvény speciális tulajdonsága
Ha $\sum_{k=- \infty}^{\infty}|R_X(u)| < \infty$ feltétel teljesül, akkor a spektrális sűrűségfüggvény közvetlenül is előállítható:
$$g_X(\lambda) = \cfrac{1}{2 \pi} \sum_{k = - \infty} ^{\infty} R_X(k) e^{-i * k *\lambda}$$
Ez tovább írható:
$$
\begin{aligned}
	g_X(\lambda) =& \cfrac{1}{ 2  \pi} \sum_{k = - \infty}^{\infty}R_X(k)cos(k \lambda) = \\
	=& \cfrac{1}{2 \pi} \left( \sigma_X^2 + 2 \sum_{k = 1}^{\infty} R_X(k) cos(k \lambda) \right)
\end{aligned}$$
#Szeidl/sztochajegyzet 