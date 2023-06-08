---
tags: OE/ALKMAT/Sztocha OE/ALKMAT/Sztocha/8tétel 
aliases: ["trajektória", "realizáció"]
TARGET DECK: 02::Sztocha
---
# trajektória
Egy tetszőleges $X_t$ folyamat trajektóriái alatt a folyamat lehetséges megvalósulását értjük.
- $X_t$ tetszőleges [[Sztochasztikus folyamatok|sztochasztikus folyamat]]
#Szeidl/sztochajegyzet 

# [[standard wiener folyamat|wiener folyamat]] trajektóriáira vonatkozó tulajdonságok
$$
\lim_{n \to \infty} \text{VAR} \left( \sum_{k=1}^{n} \left[ W\left(t_k^{(n)}\right) - W\left(t_{k-1}^{(n)}\right) \right]^2 - (t-s) \right) = 0
$$
- $W(t)$ a [[standard wiener folyamat|Wiener folyamat]],
- $t_k^{(n)}$ az időintervallumok, $t$ és $s$ közötti felosztása $n$ egyenlő részre

$$\lim_{N \to \infty} \sum_{k=1}^{2^N}\left| W \left( \cfrac{k}{2^N}\right) - W \left( \cfrac{k-1}{2^N}\right) \right| = \infty$$
- $W(t)$ a [[standard wiener folyamat|Wiener folyamat]],
- $N$ a szintek száma, amelyekre az időintervallumok fel vannak osztva ($N \to \infty$ tartalmazza a határesetet),
- $\frac{k}{2^N}$ az időintervallumok kezdőpontjai, amelyek az időtartományt $2^N$ egyenlő részre osztják,

[[standard wiener folyamat|Wiener folyamat]] 1 valószínűséggel sehol sem differenciálható. Más szóval, a [[standard wiener folyamat|Wiener folyamat]] trajektóriái az időben folyamatosan változnak, ugrásokkal és "fordulókkal", és nincsenek első deriváltjaik egyetlen pontban sem. Ez azt jelenti, hogy a [[standard wiener folyamat|Wiener folyamat]] trajektóriái nem simák, és nem lehet őket differenciálással leírni egyetlen pontban sem.

$$P\left( \max_{0 \le s \le t} W(s) \ge x\right) = 2P(W(t) \ge x) = 2 \left( 1- \Phi\left(\left( \cfrac{x}{\sqrt{t}} \right)\right) \right) $$
-   $t$: Időpont, amely az időtartamot jelöli, ahol az $x$ értéket meghaladja a [[standard wiener folyamat|Wiener folyamat]] maximuma. Ez egy valós szám, $t \geq 0$.
-   $x$: Egy küszöbérték, amely felett megvizsgáljuk a [[standard wiener folyamat|Wiener folyamat]] maximumának eloszlását az időpontban $t$. Ez egy valós szám, $x \in \mathbb{R}$.
-   $W(t)$: [[standard wiener folyamat|Wiener folyamat]] értéke az időpontban $t$. Ez egy [[Sztochasztikus folyamatok|sztochasztikus folyamat]], amelyet a Brown-mozgásként is ismerünk, és a normális eloszlású véletlen változók szummájaként definiáljuk. $W(t)$ egy valós szám.
-   $\Phi(z)$: Standard [[normális eloszlás]] eloszlásfüggvénye. Ez egy sztochasztikus változótól független függvény, amely az $z$ valós számot képezi le a $[0,1]$ intervallumra. Az $z$ változó az $x$ értéket meghaladó [[standard wiener folyamat|Wiener]] folyamatot adja vissza az időpontban $t$ normált eloszlásban.

Egy valószínűséggel fennáll az [[iterált logaritmus tétel]] a [[standard wiener folyamat|Wiener]] folyamatokra:
$$\lim \sup_{t \to \infty} \cfrac{W(t)}{\sqrt{2t \log(\log(t))}} = 1$$
$$\lim \inf_{t \to \infty} \cfrac{W(t)}{\sqrt{2t \log(\log(t))}} = -1$$
- $W(t)$: [[standard wiener folyamat|Wiener folyamat]]

#Szeidl/sztochajegyzet 

# Kártyák
START
Basic
Front:
Wiener folyamat trajektóriáira vonatkozó tulajdonságok
Back:
$$
\lim_{n \to \infty} \text{VAR} \left( \sum_{k=1}^{n} \left[ W\left(t_k^{(n)}\right) - W\left(t_{k-1}^{(n)}\right) \right]^2 - (t-s) \right) = 0
$$
- $W(t)$ a [[standard wiener folyamat|Wiener folyamat]],
- $t_k^{(n)}$ az időintervallumok, $t$ és $s$ közötti felosztása $n$ egyenlő részre

$$\lim_{N \to \infty} \sum_{k=1}^{2^N}\left| W \left( \cfrac{k}{2^N}\right) - W \left( \cfrac{k-1}{2^N}\right) \right| = \infty$$
- $W(t)$ a [[standard wiener folyamat|Wiener folyamat]],
- $N$ a szintek száma, amelyekre az időintervallumok fel vannak osztva ($N \to \infty$ tartalmazza a határesetet),
- $\frac{k}{2^N}$ az időintervallumok kezdőpontjai, amelyek az időtartományt $2^N$ egyenlő részre osztják,

[[standard wiener folyamat|Wiener folyamat]] 1 valószínűséggel sehol sem differenciálható. Más szóval, a [[standard wiener folyamat|Wiener folyamat]] trajektóriái az időben folyamatosan változnak, ugrásokkal és "fordulókkal", és nincsenek első deriváltjaik egyetlen pontban sem. Ez azt jelenti, hogy a [[standard wiener folyamat|Wiener folyamat]] trajektóriái nem simák, és nem lehet őket differenciálással leírni egyetlen pontban sem.

$$P\left( \max_{0 \le s \le t} W(s) \ge x\right) = 2P(W(t) \ge x) = 2 \left( 1- \Phi\left(\left( \cfrac{x}{\sqrt{t}} \right)\right) \right) $$
-   $t$: Időpont, amely az időtartamot jelöli, ahol az $x$ értéket meghaladja a [[standard wiener folyamat|Wiener folyamat]] maximuma. Ez egy valós szám, $t \geq 0$.
-   $x$: Egy küszöbérték, amely felett megvizsgáljuk a [[standard wiener folyamat|Wiener folyamat]] maximumának eloszlását az időpontban $t$. Ez egy valós szám, $x \in \mathbb{R}$.
-   $W(t)$: [[standard wiener folyamat|Wiener folyamat]] értéke az időpontban $t$. Ez egy [[Sztochasztikus folyamatok|sztochasztikus folyamat]], amelyet a Brown-mozgásként is ismerünk, és a normális eloszlású véletlen változók szummájaként definiáljuk. $W(t)$ egy valós szám.
-   $\Phi(z)$: Standard [[normális eloszlás]] eloszlásfüggvénye. Ez egy sztochasztikus változótól független függvény, amely az $z$ valós számot képezi le a $[0,1]$ intervallumra. Az $z$ változó az $x$ értéket meghaladó [[standard wiener folyamat|Wiener]] folyamatot adja vissza az időpontban $t$ normált eloszlásban.

Egy valószínűséggel fennáll az [[iterált logaritmus tétel]] a [[standard wiener folyamat|Wiener]] folyamatokra:
$$\lim \sup_{t \to \infty} \cfrac{W(t)}{\sqrt{2t \log(\log(t))}} = 1$$
$$\lim \inf_{t \to \infty} \cfrac{W(t)}{\sqrt{2t \log(\log(t))}} = -1$$
- $W(t)$: [[standard wiener folyamat|Wiener folyamat]]
<!--ID: 1686256793361-->
END