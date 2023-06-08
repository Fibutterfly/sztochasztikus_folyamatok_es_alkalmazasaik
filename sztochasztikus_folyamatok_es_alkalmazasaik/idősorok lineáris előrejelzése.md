---
tags: OE/ALKMAT/Sztocha OE/ALKMAT/Sztocha/5tétel 
aliases: ["lineáris előrejezés", "előrejezlés"]
TARGET DECK: 02::Sztocha
---

# idősorok lineáris előrejelzése
$$\begin{align}
	\widehat{X}_{t+k}=\sum_{s=0}^\infty a_s X_{t-s} \tag{ILE.1} \\
	\min \left(E\left( X_{t+k} -\widehat{X}_{t+k} \right)^2 \right) \tag{ILE.2}
\end{align}$$
- $X_t$ [[tágabb értelemben stacionárius|stacionárius folyamat]]
- $t$ időpont
- $k$ amennyire előre jelzünk
- $a_s$ súlyok
	- $\sum_{s=0}^\infty a_s^2 < \infty$ $\text{(ILE.3)} \tag{ILE.3}$
- legkisebb négyzetek módszerével keressük meg a megfelelő súlyokat

#Szeidl/sztochajegyzet 

# kártyák
START
Basic
Front:
idősorok lineáris előrejelzése
Back:
$$\begin{align}
	\widehat{X}_{t+k}=\sum_{s=0}^\infty a_s X_{t-s} \tag{ILE.1} \\
	\min \left(E\left( X_{t+k} -\widehat{X}_{t+k} \right)^2 \right) \tag{ILE.2}
\end{align}$$
- $X_t$ [[tágabb értelemben stacionárius|stacionárius folyamat]]
- $t$ időpont
- $k$ amennyire előre jelzünk
- $a_s$ súlyok
	- $\sum_{s=0}^\infty a_s^2 < \infty$ $\text{(ILE.3)} \tag{ILE.3}$
- legkisebb négyzetek módszerével keressük meg a megfelelő súlyokat
<!--ID: 1686244349136-->
END