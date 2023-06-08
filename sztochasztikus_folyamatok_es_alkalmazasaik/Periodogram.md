---
tags: OE/ALKMAT/Sztocha OE/ALKMAT/Sztocha/3tétel OE/ALKMAT/Sztocha/5tétel OE/ALKMAT/Sztocha/7tétel OE/ALKMAT/Sztocha/fontos_fogalom 
aliases: [""]
TARGET DECK: 02::Sztocha
---

# Periodogram
$$\begin{align}
	I_T(\lambda) =& \left( \dfrac{1}{\sqrt{T}} \sum_{k=1}^T X_k*\cos(\lambda*k) \right)^2 + \left( \dfrac{1}{\sqrt{T}} \sum_{k=1}^T X_k*\sin(\lambda*k) \right)^2 \tag{P.1} \\
	I_T(\lambda) =& \dfrac{1}{T}*\left| \sum_{k=1}^T X_k*e^{i* \lambda*k} \right|^2 \tag{P.2} \\
	I_T(\lambda) =& \sum_{k=1-T}^{T-1} \left( 1 - \dfrac{|k|}{T} \right)* \overline{R}_{ik}* \cos(\lambda*k) \tag{P.3}
\end{align}$$
- $I$ periodogram
- $T$ konstans, ablakméret
- $X_k$ idősor
- $\lambda$ frekvencia változó
- $\overline{R}_{1k} = \overline{R}_{1-k} = \dfrac{1}{T-k}*\sum_{j=1}^{T-k} X_j*X_{j+k}$ a [[kovarianciafüggvény]] becslése

#Szeidl/sztochajegyzet 

# kártya
START
Basic
Front:
Periodogram
Back:
$$\begin{align}
	I_T(\lambda) =& \left( \dfrac{1}{\sqrt{T}} \sum_{k=1}^T X_k*\cos(\lambda*k) \right)^2 + \left( \dfrac{1}{\sqrt{T}} \sum_{k=1}^T X_k*\sin(\lambda*k) \right)^2 \tag{P.1} \\
	I_T(\lambda) =& \dfrac{1}{T}*\left| \sum_{k=1}^T X_k*e^{i* \lambda*k} \right|^2 \tag{P.2} \\
	I_T(\lambda) =& \sum_{k=1-T}^{T-1} \left( 1 - \dfrac{|k|}{T} \right)* \overline{R}_{ik}* \cos(\lambda*k) \tag{P.3}
\end{align}$$
- $I$ periodogram
- $T$ konstans, ablakméret
- $X_k$ idősor
- $\lambda$ frekvencia változó
- $\overline{R}_{1k} = \overline{R}_{1-k} = \dfrac{1}{T-k}*\sum_{j=1}^{T-k} X_j*X_{j+k}$ a [[kovarianciafüggvény]] becslése
<!--ID: 1686256182562-->
END