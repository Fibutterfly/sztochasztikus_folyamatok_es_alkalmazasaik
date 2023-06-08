---
tags: OE/ALKMAT/Sztocha OE/ALKMAT/Sztocha/9tétel 
aliases: ["Ito-féle sztochasztikus integrálást"]
TARGET DECK: 02::Sztocha
---

# Ito-féle [[sztochasztikus integrál]]
$$I(t) = \int_0^T X(t) dW(t) = \sum_{k=0}^{n-1}(X(t_k)*[W(t_{k+1}) - W(t_k)]) + X(t_n)*[W(t)-W(t_n)]$$
- $X$ [[Sztochasztikus folyamatok|Sztochasztikus folyamat]], amely az $\mathcal{F}(t)$ szűréshez igazodik
	- Ezt lépcsős formában fogjuk felhasználni, amely azt jelenti, hogy addig bontjuk egyenlő részekre, amíg nem tudjuk lépcsőként felfogni, akár végtelenül sokáig finomítjuk a lépés közöket ehhez.
- $W(t)$ [[standard wiener folyamat|wiener folyamat]]
	- $dW(t)$ a [[standard wiener folyamat|wiener folyamat]] növekménye
- $I(t)$ az Ito Integrál
	- Szintén egy [[Sztochasztikus folyamatok|sztochasztikus folyamat]].

Ahhoz, hogy számolni tudjunk ezzel a következő feltételezéssel szoktunk élni:
$$\lim_{m \to \infty} f_n(t) \approx X(t)$$
- $f_n$ egyszerű, közönséges függvények
	- sokszor ezeket lépcsőnként választjuk, de nincs megkötés rá.

Így átalakítva a következő formulát kapjuk:
$$\int_0^t X(u) dW(u) = \lim_{n \to \infty} \int_0^t f_n(u) dW(u)$$
#Joydeep/Mathematical_finnance

# Ito-féle [[sztochasztikus integrál]] tulajdonságai
- Martingál
- Izometrikus $$E(I^2(t)) = E \int_0^t X^2(\lambda)d\lambda= ||I(t)||^2_{L^2}$$
- létezik a négyzetes varianciája, ami szintén egy [[Sztochasztikus folyamatok|sztochasztikus folyamat]] $$[I,I](t)= E \int_0^t X^2(\lambda)d\lambda$$
- $\mathcal{F}_t$ mérhető
- Minden tulajdonság igaz rá, amely a [[Stielejtes integrál|Stielejtes integrálra]]
#Joydeep/Mathematical_finnance

# kártya
START
Basic
Front:
Ito-féle [[sztochasztikus integrál]]
Back:
$$I(t) = \int_0^T X(t) dW(t) = \sum_{k=0}^{n-1}(X(t_k)*[W(t_{k+1}) - W(t_k)]) + X(t_n)*[W(t)-W(t_n)]$$
- $X$ [[Sztochasztikus folyamatok|Sztochasztikus folyamat]], amely az $\mathcal{F}(t)$ szűréshez igazodik
	- Ezt lépcsős formában fogjuk felhasználni, amely azt jelenti, hogy addig bontjuk egyenlő részekre, amíg nem tudjuk lépcsőként felfogni, akár végtelenül sokáig finomítjuk a lépés közöket ehhez.
- $W(t)$ [[standard wiener folyamat|wiener folyamat]]
	- $dW(t)$ a [[standard wiener folyamat|wiener folyamat]] növekménye
- $I(t)$ az Ito Integrál
	- Szintén egy [[Sztochasztikus folyamatok|sztochasztikus folyamat]].

Ahhoz, hogy számolni tudjunk ezzel a következő feltételezéssel szoktunk élni:
$$\lim_{m \to \infty} f_n(t) \approx X(t)$$
- $f_n$ egyszerű, közönséges függvények
	- sokszor ezeket lépcsőnként választjuk, de nincs megkötés rá.

Így átalakítva a következő formulát kapjuk:
$$\int_0^t X(u) dW(u) = \lim_{n \to \infty} \int_0^t f_n(u) dW(u)$$
<!--ID: 1686257902923-->
END