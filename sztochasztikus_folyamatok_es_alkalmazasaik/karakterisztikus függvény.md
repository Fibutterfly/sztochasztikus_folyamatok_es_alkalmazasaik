---
tags: OE/ALKMAT/Sztocha OE/ALKMAT/Sztocha/fontos_fogalom 
aliases: ["karakterisztikus polinom", "karakterisztikus polinomjának"]
TARGET DECK: 02::Sztocha
---

# Karakterisztikus függvény
$$\phi_X(s) = E(e^{i*s*X}) = E(cos(sX) + i*sin(s*X))$$
Ahol:
- $s \in \mathbb{R}$
- $i$ a képzeletbeli szám
- $X$ [[valószínűségi változó]].

Ezt előtudjuk állítani a következőképpen:
$$\phi_X(s) = \int_{- \infty}^\infty e^{i*s*x} dF_X (x)$$.
Ezt diszkrét és folytonos esetben a következőképpen fejezzük ki:
$$\phi_X (s) = \sum_{k=0}^\infty p_k e^{i* x_k*s}$$
$$\phi_X(s) = \int_{- \infty}^\infty e^{i*x*s} f_X(x)dx$$.

#Michelberger/alkalmazott_folyamatstatisztika 
## Karakterisztikus függvény tulajdonságai
- Akkor és csak akkor valós, ha az eloszlás szimmetrikus
- Ha létezik $k$. momentum, akkor a karakterisztikus függvény $k$-szor deriválható a $0$ pontban
- $E(X^k) = \dfrac{\phi_X^{(k)} (0)}{i^k}$
- Független valószínűségi változók összességének karakteriksztus függvénye megegyezik a karakterisztikus függvényeik szorzatával

#Michelberger/alkalmazott_folyamatstatisztika 

# kártyák
START
Basic
Front:
Karakterisztikus függvény
Back:
$$\phi_X(s) = E(e^{i*s*X}) = E(cos(sX) + i*sin(s*X))$$
Ahol:
- $s \in \mathbb{R}$
- $i$ a képzeletbeli szám
- $X$ [[valószínűségi változó]].

Ezt előtudjuk állítani a következőképpen:
$$\phi_X(s) = \int_{- \infty}^\infty e^{i*s*x} dF_X (x)$$.
Ezt diszkrét és folytonos esetben a következőképpen fejezzük ki:
$$\phi_X (s) = \sum_{k=0}^\infty p_k e^{i* x_k*s}$$
$$\phi_X(s) = \int_{- \infty}^\infty e^{i*x*s} f_X(x)dx$$.
<!--ID: 1686260404237-->
END

START
Basic
Front:
Karakterisztikus függvény tulajdonságai
Back:
- Akkor és csak akkor valós, ha az eloszlás szimmetrikus
- Ha létezik $k$. momentum, akkor a karakterisztikus függvény $k$-szor deriválható a $0$ pontban
- $E(X^k) = \dfrac{\phi_X^{(k)} (0)}{i^k}$
- Független valószínűségi változók összességének karakteriksztus függvénye megegyezik a karakterisztikus függvényeik szorzatával
<!--ID: 1686260404243-->
END