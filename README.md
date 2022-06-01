# LE PROBLÈME D'ARBITRAGE:

***


> ### 24-3   Arbitrage
> L'arbitrage consiste à utiliser les écarts de taux de change pour transformer une unité d'une devise en plusieurs unités de la même devise. Par exemple, supposons que « 1 » dollar américain achète « 49 » roupies indiennes, « 1 » roupie indienne achète « 2 » yen japonais et « 1 » yen japonais achète « 0,0107 » dollar américain. Ensuite, en convertissant les devises, un trader peut commencer avec « 1 » dollar américain et acheter « 49 x 2 x 0,0107 = 1,0486 » dollars américains, réalisant ainsi un bénéfice de « 4,86 ».

> Supposons qu'on nous donne n devises `c1, c2, ..., cn` et une table `n x n` `R` de taux de change, telle qu'une unité de devise `ci` achète `R[i, j]` unités de devise **`cj`**.

> **a.** Donner un algorithme efﬁcace pour déterminer s'il existe ou non une suite de monnaies `{ci1, ci2, ..., cik}` telle que
> `R[i1, i2] * R[i2, i3] ... R[ik-1, ik] * R[ik, i1] > 1.`
> Analysez le temps d'exécution de votre algorithme.

> **b.** Donner un algorithme efﬁcace pour imprimer une telle séquence s'il en existe un. Analysez le temps d'exécution de votre algorithme.


***

### Taux de change de toutes les banques
![currency-rates-of-banks](http://www.mycertnotes.com/wp-content/uploads/2017/11/currency-rates-of-banks.jpg)


***

### Graphique des devises :
![arbitrage-graph](http://www.mycertnotes.com/wp-content/uploads/2017/11/arbitrage-graph.png)


***

### Bellman-Ford Algorithm
![Bellman-Ford-Algorithm](http://www.mycertnotes.com/wp-content/uploads/2017/11/Bellman-Ford-Algorithm.png)



***

 
### Arbitrage Occasion:                 
 
**Arbitrage 1: (profit - 32.99 AZN)**
* 1000.0000 AZN = 507.6142 EUR (Bank Melli İran)
*  507.6142 EUR = 1032.9949 AZN (AmrahBank)
 
**Arbitrage 2: (profit - 3.16 AZN)**
* 1000.0000 AZN =  451.2635 GBP (AccessBank)
*  451.2635 GBP = 1003.1588 AZN (Gunay Bank)
 
**Arbitrage 3: (profit - 28.07 AZN)** 
*  1000.0000 AZN = 35087.7193 RUB (AccessBank)
* 35087.7193 RUB =  1028.0702 AZN (Azərpoçt)
 
**Arbitrage 4: (profit - 30.57 AZN)**
* 1000.0000 AZN =  507.6142 EUR (Bank Melli İran)
*  507.6142 EUR =  607.2868 USD (AmrahBank)
*  607.2868 USD = 1030.5658 AZN (AmrahBank)
 
**Arbitrage 5: (profit - 0.21 AZN)** 
* 1000.0000 AZN =  451.2635 GBP (AccessBank)
*  451.2635 GBP =  589.4000 USD (Gunay Bank)
*  589.4000 USD = 1000.2118 AZN (AmrahBank)
 
**Arbitrage 6: (profit - 25.65 AZN)** 
* 1000.0000 AZN = 35087.7193 RUB (AccessBank)
* 35087.7193 RUB = 604.3916 USD (DəmirBank)
* 604.3916 USD = 1025.6526 AZN (AmrahBank)
 
....................................
  
 
**Arbitrage 56: (profit - 3.87 AZN)** 
* 1000.0000 AZN = 507.6142 EUR (Bank Melli İran)
* 507.6142 EUR = 2028.4325 TRY (PAŞA Bank)
* 2028.4325 TRY = 442.6328 GBP (PAŞA Bank)
* 442.6328 GBP = 578.1273 USD (Gunay Bank)
* 578.1273 USD = 34261.6497 RUB (AccessBank)
* 34261.6497 RUB = 1003.8663 AZN (Azərpoçt)
 
**Arbitrage 57: (profit - 5.46 AZN)** 
* 1000.0000 AZN = 35087.7193 RUB (AccessBank)
* 35087.7193 RUB = 461.0180 GBP (DəmirBank)
* 461.0180 GBP = 602.1405 USD (Gunay Bank)
* 602.1405 USD = 513.5005 EUR (Bank Melli İran)
* 513.5005 EUR = 2051.9541 TRY (PAŞA Bank)
* 2051.9541 TRY = 1005.4575 AZN (PAŞA Bank)
 
**Arbitrage 58: (profit - 13.69 AZN)** 
* 1000.0000 AZN = 507.6142 EUR (Bank Melli İran)
* 507.6142 EUR = 607.2868 USD (AmrahBank)
* 607.2868 USD = 35989.7362 RUB (AccessBank)
* 35989.7362 RUB = 472.8696 GBP (DəmirBank)
* 472.8696 GBP = 2068.7457 TRY (PAŞA Bank)
* 2068.7457 TRY = 1013.6854 AZN (PAŞA Bank)
 












