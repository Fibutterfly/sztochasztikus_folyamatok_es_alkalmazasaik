---
tags: OE/ALKMAT/Sztocha 
aliases: ["kauzális folyamatok"]
---
# Kauzális folyamat
A kauzális folyamat olyan [[lineáris folyamatok|lineáris folyamat]], amely előállítható a következő képen:
$$X_t = \sum_{s  =0}^\infty a_s \epsilon_{t-s}$$
Emellett az $X_t$ csak a múltjától függ. Ezen felül egy [[lineáris folyamatok|lineáris folyamat]] akkor és csak akkor kauzális folyamat, ha a [[spektrális sűrűségfüggvény|spektrális sűrűségfüggvénye]] létezik és teljesül rá a [[Bochner-Kolmogorov tétel]]:
$$\int_{- \pi}^\pi \ln(g_X(\lambda))d \lambda > -\infty$$
ahol:
- $g_X$ a [[spektrális sűrűségfüggvény]]
- $\lambda$ időbeli változások sebességét leíró paraméter
#Szeidl/sztochajegyzet 

# Kauzális folyamat [[spektrális sűrűségfüggvény|spektruma]]
1.  Az [[spektrális sűrűségfüggvény]] valós, páros és integrálható az egész valós tengelyen.
2.  Az [[spektrális sűrűségfüggvény]] [[Fourier]]-transzformáltja az [[autokorrelációs függvény]].
3.  Az [[spektrális sűrűségfüggvény]] [[Fourier]]-transzformáltja, azaz az [[autokorrelációs függvény]] [[Fourier]]-transzformáltja is valós és páros.
4.  Az [[spektrális sűrűségfüggvény]] mindenhol nemnegatív.
5.  A kauzális folyamat [[spektrális sűrűségfüggvény|spektruma]] monoton csökken a pozitív frekvenciákkal.
6.  Ha az [[spektrális sűrűségfüggvény]] Lévy-féle függvény, akkor az ehhez tartozó kauzális folyamat időben szigorúan [[tágabb értelemben stacionárius|stacionárius]], azaz statisztikai tulajdonságai időben állandók.
7.  Az spektrális sűrűségfüggvénynek teljesülnie kell a [[Bochner-Kolmogorov tétel|Bochner-Kolmogorov]] tételt, vagyis az integrálja a logaritmusának az egész valós tengelyen végesnek kell lennie.
#chatGPT 

# Kauzális folyamat [[spektrális sűrűségfüggvény|spektrumára]] lévő hatása a [[transzfer függvény|transzfer függvénynek]]
$H \left(e^{-i \lambda} \right)$ esetén a kauzális folyamat [[spektrális sűrűségfüggvény|spektrális sűrűségfüggvénye]] a
$$g_X(\lambda) = \cfrac{\sigma_\epsilon^2}{2 \pi} \left| \sum_{t=0}^\infty a_t e^{-it\lambda}\right|^2$$ lesz.
#Szeidl/sztochajegyzet 