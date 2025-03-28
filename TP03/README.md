# TP3 - Apprentissage par Renforcement : Q-Learning vs SARSA

## Objectif
L'objectif de ce TP est de comparer les performances de deux algorithmes d'apprentissage par renforcement : **Q-Learning** et **SARSA**. Nous analysons leur comportement en observant les récompenses obtenues au fil des épisodes et l'évolution des récompenses cumulées.

---

## 1. Récompenses obtenues par épisode - Q-Learning
![Q-Learning Rewards](/TP03/img/1.png)

Ce graphique montre l'évolution des récompenses obtenues à chaque épisode en utilisant l'algorithme **Q-Learning**.  
Nous constatons une tendance décroissante, ce qui peut indiquer une stratégie sous-optimale ou un mauvais réglage des hyperparamètres.

---

## 2. Récompenses obtenues par épisode - SARSA
![SARSA Rewards](/TP03/img/2.png)

Ici, nous observons la variation des récompenses obtenues par épisode avec **SARSA**.  
Comparé au Q-Learning, SARSA semble plus stable et maintient des valeurs plus élevées de récompenses.

---

## 3. Récompenses cumulées
![Récompenses cumulées](/TP03/img/3.png)

Ce graphique compare la somme des récompenses cumulées pour **Q-Learning** et **SARSA**.  
On remarque que **SARSA** accumule beaucoup plus de récompenses sur la durée, suggérant une meilleure convergence vers une politique efficace.

---

## 4. Comparaison des récompenses par épisode : Q-Learning vs SARSA
![Comparaison Q-Learning vs SARSA](/TP03/img/4.png)

Ce graphique met en évidence l'évolution des récompenses pour **Q-Learning** et **SARSA** sur plusieurs épisodes :
- **Q-Learning** présente une tendance descendante, indiquant une convergence plus difficile.
- **SARSA** maintient des récompenses plus élevées, suggérant une stratégie plus prudente et efficace.

---

## Conclusion
D'après les résultats observés :
- **SARSA semble plus stable** et génère des récompenses plus élevées sur le long terme.
- **Q-Learning** montre une forte variabilité et semble moins performant avec les hyperparamètres utilisés.

---