---
tags: OE/ALKMAT/Sztocha OE/ALKMAT/Sztocha/5tétel 
aliases: [""]
TARGET DECK: 02::Sztocha
---

# [[standard wiener folyamat|Wiener]]-szűrő
$$\begin{align}
	&\widehat{Y} = \sum_{j=0}^\infty h(j) X_{t-j} \tag{WSz.1} \\
	&\begin{aligned}
		E(Y_t - \widehat{Y})^2 =
			&R_{YY}(0) - 2*\sum_{j=0}^{\infty} h(j) * R_{YX}(j) +\\
			&+ \sum_{j=0}^\infty \sum_{m=0}^\infty h(j)*h(m)*R_{XX}(j-m)
	\end{aligned}\tag{WSz.2}
\end{align}$$
- $(Y_t, X_t)$ együttesen [[tágabb értelemben stacionárius|stacionárius folyamat]]
- $t$ időpont
- $h$ egy [[transzfer függvény|transzferfüggvény]]
	- ezeket úgy választjuk meg, hogy minimalizálják a négyzetes hibát
- $R_{XX}(i), R_{YY}(i)$ [[autokovariancia függvény]]
- $R_{YX}(i)$ [[keresztkovariancia függvény]]

#Szeidl/sztochajegyzet 

# kártyák
START
Basic
Front:
Wiener-szűrő
Back:
$$\begin{align}
	&\widehat{Y} = \sum_{j=0}^\infty h(j) X_{t-j} \tag{WSz.1} \\
	&\begin{aligned}
		E(Y_t - \widehat{Y})^2 =
			&R_{YY}(0) - 2*\sum_{j=0}^{\infty} h(j) * R_{YX}(j) +\\
			&+ \sum_{j=0}^\infty \sum_{m=0}^\infty h(j)*h(m)*R_{XX}(j-m)
	\end{aligned}\tag{WSz.2}
\end{align}$$
- $(Y_t, X_t)$ együttesen [[tágabb értelemben stacionárius|stacionárius folyamat]]
- $t$ időpont
- $h$ egy [[transzfer függvény|transzferfüggvény]]
	- ezeket úgy választjuk meg, hogy minimalizálják a négyzetes hibát
- $R_{XX}(i), R_{YY}(i)$ [[autokovariancia függvény]]
- $R_{YX}(i)$ [[keresztkovariancia függvény]]
<!--ID: 1686246504091-->
END