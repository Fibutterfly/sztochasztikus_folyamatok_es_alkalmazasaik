---
tags: OE/ALKMAT/Sztocha 
aliases: ["iterált logaritmus formula","iterált logaritmus tételből"]
---
# iterált logaritmus tétel
A következő összefüggések $1$ valószínűséggel fennállnak
$$\lim_{n \to \infty} \sup \dfrac{\sum_{i=1}^n(X_i) - n* E(X_n)}{\sqrt[2]{2*n*\ln(\ln(n))}} = + | \sigma|$$
és
$$\lim_{n \to \infty} \inf \dfrac{\sum_{i=1}^n(X_i) - n* E(X_n)}{\sqrt[2]{2*n*\ln(\ln(n))}} = - | \sigma|$$
Ahol:
- $VAR(X_n) = \sigma^2 < \infty$
- $X_i$ független, azonos eloszlású [[valószínűségi változó|valószínűségi változók]]
- $E(X_n) = E(X_1) = \dots = E(X_{n-1})$
#Ludwig/Szotchasztikus_differenciál 