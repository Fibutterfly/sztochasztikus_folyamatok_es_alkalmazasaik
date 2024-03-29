---
tags: OE/ALKMAT/Sztocha OE/ALKMAT/Sztocha/4tétel OE/ALKMAT/Sztocha/fontos_fogalom 
aliases: ["lineáris folyamat"]
TARGET DECK: 02::Sztocha
---

# lineáris folyamatok
- [[lineáris szűrő|lineáris szűrők]]
- ARMA folyamatok
- Lineáris előrejezés
- [[standard wiener folyamat|Wiener]]-szűrő
- Kálmán-szűrő
Azt a $X_t$ folyamatot nevezzük lineáris folyamatnak, amely teljesíti  a következő:
$$X_t = \sum_{s= -\infty}^{\infty} a_s \epsilon_{t-s}$$
Ahol:
- $X_t$ [[Sztochasztikus folyamatok|sztochasztikus folyamat]]
- $a_s \in \mathbb{R}$, $\sum_{s = - \infty}^{\infty} a_s^2 < \infty$
- $\epsilon$ [[fehérzaj folyamat]], $\sigma_\epsilon^2 > 0$
- $\lim_{m,n \to \infty} E \left(X_t - \sum_{s = -m}^n a_s \epsilon_{t-s} \right)^2 = 0$

#Szeidl/sztochajegyzet 


# kártya
START
Basic
Front:
lineáris folyamatok
Back:
- [[lineáris szűrő|lineáris szűrők]]
- ARMA folyamatok
- Lineáris előrejezés
- [[standard wiener folyamat|Wiener]]-szűrő
- Kálmán-szűrő
Azt a $X_t$ folyamatot nevezzük lineáris folyamatnak, amely teljesíti  a következő:
$$X_t = \sum_{s= -\infty}^{\infty} a_s \epsilon_{t-s}$$
Ahol:
- $X_t$ [[Sztochasztikus folyamatok|sztochasztikus folyamat]]
- $a_s \in \mathbb{R}$, $\sum_{s = - \infty}^{\infty} a_s^2 < \infty$
- $\epsilon$ [[fehérzaj folyamat]], $\sigma_\epsilon^2 > 0$
- $\lim_{m,n \to \infty} E \left(X_t - \sum_{s = -m}^n a_s \epsilon_{t-s} \right)^2 = 0$
<!--ID: 1686166795238-->
END