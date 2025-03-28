# Reinforcement Learning TPs

Ce dépôt contient une série de travaux pratiques (TP) visant à explorer et implémenter des algorithmes d'apprentissage par renforcement (RL). Chaque TP est structuré dans un dossier distinct avec un README détaillant ses objectifs et les étapes de réalisation.

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/uameless/reinforcement-learning.git
   ```
2. (Optional) Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install the necessary libraries:
   ```bash
   pip install -r requirements.txt
   ```
   
## Table des matières
- [TP1 - Introduction à OpenAI Gym](#tp1---introduction-à-openai-gym)
- [TP2 - Implémentation de Q-Learning](#tp2---implémentation-de-q-learning)
- [TP3 - Optimisation des Feux de Circulation](#tp3---optimisation-des-feux-de-circulation)
- [TP4 - Implémentation de PPO](#tp4---implémentation-de-ppo)

---

## TP1 - Introduction à OpenAI Gym

### Objectif
L'objectif de ce TP est de se familiariser avec les outils essentiels du Reinforcement Learning (RL), notamment OpenAI Gym. Les étudiants vont explorer comment interagir avec un environnement RL et exécuter des actions avant d'implémenter un algorithme d'apprentissage dans les séances suivantes.

### Contenu
- Découverte de l'environnement OpenAI Gym
- Interaction avec un environnement RL
- Exécution d'actions et observation des retours
- Analyse des observations et des récompenses reçues

### Fichiers
- `tp1/README.md` - Instructions détaillées
- `tp1/code/` - Scripts d'exploration

---

## TP2 - Implémentation de Q-Learning

### Objectif
L'objectif de ce TP est de mettre en pratique les concepts fondamentaux de l'apprentissage par renforcement en explorant l'algorithme Q-Learning. Les étudiants vont :
- Implémenter Q-Learning
- Explorer les stratégies d'exploration et d'exploitation
- Analyser la convergence des valeurs Q avec FrozenLake (OpenAI Gym)

### Contenu
- Introduction à Q-Learning et son fonctionnement
- Implémentation de l'algorithme pas à pas
- Utilisation de la Q-table pour la prise de décision
- Visualisation et évaluation des performances

### Fichiers
- `tp2/README.md` - Explications et consignes
- `tp2/code/` - Scripts pour Q-Learning

---

## TP3 - Optimisation des Feux de Circulation

### Objectif
L'objectif de ce TP est d'explorer l'optimisation des feux de circulation à l'aide de l'apprentissage par renforcement. Les étudiants vont :
- Découvrir un environnement simulé de gestion du trafic
- Implémenter Q-Learning et SARSA
- Comparer les performances des deux algorithmes

### Contenu
- Modélisation d'un réseau de feux de circulation
- Implémentation de Q-Learning et SARSA
- Analyse comparative des performances
- Visualisation des résultats sous forme de graphiques

### Fichiers
- `tp3/README.md` - Détails du TP
- `tp3/code/` - Implémentations des algorithmes

---

## TP4 - Implémentation de PPO

### Objectif
L'objectif de ce TP est de familiariser les étudiants avec l'implémentation de l'algorithme Proximal Policy Optimization (PPO). Ce TP inclut :
- Construction d'une table de politiques
- Mise à jour des valeurs des états
- Entraînement d'un agent dans l'environnement Taxi-v3

### Contenu
- Introduction à PPO et ses avantages
- Implémentation et entraînement de l'agent
- Ajustement des hyperparamètres pour améliorer la performance
- Analyse des résultats et comparaison avec d'autres méthodes

### Fichiers
- `tp4/README.md` - Instructions détaillées
- `tp4/code/` - Implémentation de PPO

---

## Réalisé par
**EL HACHYMI Ahmed Yassine**

## Supervisé par :
**Professeur Mohemed Khalifa Boutahir**

---
