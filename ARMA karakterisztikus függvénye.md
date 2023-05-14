---
tags: OE/ALKMAT/Sztocha 
aliases:
---

# ARMA karakterisztikus függvénye
Az [[ARMA folyamat]] karakterisztikus függvénye előáll a [[modell]] [[Autoregresszív modell (AR)|autoregresszív]] és [[mozgóátlag modell (MA)|mozgóátlag]] polinomjainak karakterisztikus függvényeinek szorzataként:
$$\phi_{ARMA}(s) = \dfrac{\phi_{AR}(s)}{\theta_{MA}(s)}$$
Ahol:
- $\phi_{AR}(s)$ az [[Autoregresszív modell (AR)|autoregresszív]] polinom karakterisztikus függvénye
- $\theta_{MA}(s)$ a [[mozgóátlag modell (MA)|mozgóátlag]] polinom karakterisztikus függvénye.

Az [[Autoregresszív modell (AR)|autoregresszív]] és [[mozgóátlag modell (MA)|mozgóátlag]] polinom karakterisztikus függvényei az alábbi módon adódnak:
$$\phi_{AR}(s) = 1 - \sum_{i=1}^p \phi_i e^{-is}$$
$$\theta_{MA}(s) = 1 + \sum_{i=1}^q \theta_i e^{-is}$$
Ahol $p$ az [[Autoregresszív modell (AR)|autoregresszív]] polinom fokszáma, $q$ pedig a [[mozgóátlag modell (MA)|mozgóátlag]] polinom fokszáma.

Az [[ARMA folyamat|ARMA modell]] karakterisztikus egyenletének megoldásai - amelyek a [[suli/02 ALKMAT/sztochasztikus_folyamatok_es_alkalmazasaik/karakterisztikus függvény|karakterisztikus függvény]] gyökei - a [[modell]] stabilitását határozzák meg, és ezek a gyökök az egységkörön lehetnek. Ha az összes gyök a egységkörön belül van, akkor az [[ARMA folyamat|ARMA modell]] stabil, vagyis a [[modell]] hosszú távon is kiszámítható, ,tehát [[kauzális folyamat]] míg ha van gyök a egységkörön kívül, akkor az [[ARMA folyamat|ARMA modell]] instabil, és a [[modell]] hosszú távon nem kiszámítható.

#chatGPT 