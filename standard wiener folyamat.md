---
tags: OE/ALKMAT/Sztocha 
aliases: ["Brown mozgás","wiener", "wiener folyamat"]
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
![[Pasted image 20230403195445.png]]
![[Pasted image 20230403195451.png]]
![[Pasted image 20230403195500.png]]
![[Pasted image 20230403195539.png]]
![[Pasted image 20230403195546.png]]
![[Pasted image 20230403195551.png]]
![[Pasted image 20230403195628.png]]
## Standard-wiener folyamat plusz tulajdonságai
![[Pasted image 20230403200139.png]]
![[Pasted image 20230403200204.png]]
# wiener folyamat trajektóriáira vonatkozó tulajdonságok
![[Pasted image 20230403195754.png]]
![[Pasted image 20230403195813.png]]
![[Pasted image 20230403195824.png]]
![[Pasted image 20230403195844.png]]
![[Pasted image 20230403195900.png]]
![[Pasted image 20230403195910.png]]
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
![[Pasted image 20230403200041.png]]

#Szeidl/sztochajegyzet 
# [[Fehérzaj folyamat|fehérzaj]] [[spektrális sűrűségfüggvény|spektrális sűrűségfüggvénye]]
![[Pasted image 20230403205914.png]]
#Szeidl/sztochajegyzet 