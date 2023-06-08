---
tags: OE/ALKMAT/Sztocha OE/ALKMAT/Sztocha/fontos_fogalom 
aliases: ["ARMA modell"]
TARGET DECK: 02::Sztocha
---
# ARMA folyamat
Az ARMA folyamat előállítása az [[mozgóátlag modell (MA)|mozgóátlag modell]] és az [[Autoregresszív modell (AR)|autoregresszív modell]] segítségével történik :
$$AR|MA(p,q) = \sum_{k = 1}^p (c_k x_{t-k}) + \sum_{k=1}^q(d_k \epsilon_{t-k}) + \epsilon_t$$
- $p,q \in \mathbb{Z}^+$
	- $p$ az [[Autoregresszív modell (AR)|autoregresszív modell]] rendje
	- $q$ a [[mozgóátlag modell (MA)|mozgóátlag modell]] rendje
- $c_k$ a $t-k.$ időponthoz tartozó [[autoregressziós együttható]]
- $x_k$ a $k.$ időponthoz tartozó [[tágabb értelemben stacionárius|stacionárius folyamat]] értéke
- $d_k$ a $t-k.$ időponthoz tartozó [[mozgóátlag együttható]]
- $\epsilon_t$ [[Fehérzaj folyamat|fehérzaj]]
#Szeidl/sztochajegyzet 
# ARMA [[kauzális folyamat]]
![[Pasted image 20230403212841.png]]
#Szeidl/sztochajegyzet 

# ARMA [[modell]] paraméter becslése
Az ARMA modellek paraméterbecslési módszerei közé tartoznak:

1.  [[Legkisebb négyzetek módszere]] (Least Squares Method): Az [[Autoregresszív modell (AR)|autoregresszív]] és mozgó átlag paramétereket olyan módon becsülik meg, hogy minimalizálják a sztochasztikus hiba négyzetösszegét. A módszer a Gauss-Markov tételre támaszkodik, amely kimondja, hogy ha az eredeti modellhibák iid (függetlenek, azonos eloszlásúak), akkor a becslési paraméterek hatékonyak lesznek.
2.  [[Maximum likelihood módszer]]: Ez a módszer a legvalószínűbb paramétereket keresi, amelyekkel az adatok valószínűsége a legnagyobb. Ez azt jelenti, hogy az adott paraméterek mellett a [[modell]] azt a legjobban magyarázza az adatokat.
3.  Bayes-i módszer: Ez a módszer a priori eloszlásokat használja a paraméterekre, és a poszteriori eloszlásokat kiszámítja a paraméterek meghatározása után. A módszer előnye, hogy az a priori tudásunkat be tudjuk építeni a modellezésbe, és a módszer rugalmasabb a modellhibák eloszlásának kezelésében.
4.  Burg módszer: Ez a módszer az [[Autoregresszív modell (AR)|autoregresszív]] [[modell]] paramétereit úgy becsüli meg, hogy a reflexiós együtthatókat (reflection coefficients) használja. A reflexiós együtthatók olyan paraméterek, amelyek a [[modell]] autokorrelációs függvényének kiszámítására használhatók.
5.  Hannan-Rissanen módszer: Ez a módszer az ARMA [[modell]] paramétereit úgy becsüli meg, hogy először egy [[Autoregresszív modell (AR)|autoregresszív]] modellt illeszt a megfigyelt adatokra, majd az [[Autoregresszív modell (AR)|autoregresszív]] modellből kiindulva hozzáadja a mozgó átlag paramétereit. Ez a módszer hatékonyabb lehet, mint az ARMA [[modell]] közvetlen illesztése.
6.  Conditional Sum of Squares módszer: Ez a módszer az [[Autoregresszív modell (AR)|autoregresszív]] és mozgó átlag paramétereit úgy becsüli meg, hogy a modellhibák kvadratikus összegét (CSS) minimalizálja. Ez a módszer hasonló a legkisebb négyzetek módszeréhez, de hatékonyabb lehet az idősorok becslésében.

Fontos megjegyezni, hogy a különböző módszerek eredményei eltérőek lehetnek, és a választásuk a modellhez kapcsolódó adatok és a vizsgálat céljától függenek.
#chatGPT 

# kártya
START
Basic
Front:
ARMA folyamat
Back:
Az ARMA folyamat előállítása az [[mozgóátlag modell (MA)|mozgóátlag modell]] és az [[Autoregresszív modell (AR)|autoregresszív modell]] segítségével történik :
$$AR|MA(p,q) = \sum_{k = 1}^p (c_k x_{t-k}) + \sum_{k=1}^q(d_k \epsilon_{t-k}) + \epsilon_t$$
- $p,q \in \mathbb{Z}^+$
	- $p$ az [[Autoregresszív modell (AR)|autoregresszív modell]] rendje
	- $q$ a [[mozgóátlag modell (MA)|mozgóátlag modell]] rendje
- $c_k$ a $t-k.$ időponthoz tartozó [[autoregressziós együttható]]
- $x_k$ a $k.$ időponthoz tartozó [[tágabb értelemben stacionárius|stacionárius folyamat]] értéke
- $d_k$ a $t-k.$ időponthoz tartozó [[mozgóátlag együttható]]
- $\epsilon_t$ [[Fehérzaj folyamat|fehérzaj]]
<!--ID: 1686259816374-->
END