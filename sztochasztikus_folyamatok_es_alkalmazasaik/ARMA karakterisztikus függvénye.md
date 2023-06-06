---
tags: OE/ALKMAT/Sztocha 
aliases:
---

# ARMA [[spektrális sűrűségfüggvény|spektruma]]
$$g_X(\lambda) = \dfrac{\sigma^2_\epsilon}{2*\pi} \left| \dfrac{Q(e^{i*\lambda})}{P(e^{i*\lambda})} \right|^2$$
Ahol:
- $g$ az [[ARMA folyamat]] [[spektrális sűrűségfüggvény|spektruma]]
- $X$ [[Sztochasztikus folyamatok|sztochasztikus folyamat]]
- $\lambda$ a frekvencia változása
- $Q$ a [[mozgóátlag modell (MA)|mozgóátlag modell]] karakterisztikus polinomja
- $P$ az [[Autoregresszív modell (AR)|autoregresszív]] [[modell]] karakterisztikus polinomja

Az [[ARMA folyamat|ARMA modell]] karakterisztikus egyenletének megoldásai - amelyek a [[suli/02 ALKMAT/sztochasztikus_folyamatok_es_alkalmazasaik/karakterisztikus függvény|karakterisztikus függvény]] gyökei - a [[modell]] stabilitását határozzák meg, és ezek a gyökök az egységkörön ==kívül== lehetnek. Ha az összes gyök a egységkörön belül van, akkor az [[ARMA folyamat|ARMA modell]] stabil, vagyis a [[modell]] hosszú távon is kiszámítható, ,tehát [[kauzális folyamat]] míg ha van gyök a egységkörön kívül, akkor az [[ARMA folyamat|ARMA modell]] instabil, és a [[modell]] hosszú távon nem kiszámítható.

#chatGPT 
#Budai/Idősorok_osztályozása 