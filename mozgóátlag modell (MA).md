---
tags: OE/ALKMAT/Sztocha 
aliases: ["mozgóátlag", "mozgóátlag modell", "MA", "mozgóátlag-operátor", "mozgóátlag-modell"]
---
# mozgóátlag [[modell]] (MA)
A mozgóátlag modellnek a következőt szokás hívni:
$$X_t = \mu + \epsilon_t + \sum_{k = 1}^q d_k*\epsilon_{t-k}$$
Ahol:
-   $X_t$ az időpillanat $t$-beli megfigyelt érték
-   $\mu$ a [[várható érték]]
-   $\epsilon_t$ [[Fehérzaj folyamat|fehér zaj]], azaz $\epsilon_t \sim WN(0, \sigma^2)$
- $d_k$ a mozgóátlag paraméterei, melyek meghatározzák a késleltetett [[Fehérzaj folyamat|fehér zaj]] lineáris kombinációját.

#chatGPT 