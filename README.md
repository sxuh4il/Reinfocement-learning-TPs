# Travaux Pratiques en Reinforcement Learning

## 📌 Présentation
Ce dépôt propose une série de quatre Travaux Pratiques (TP) en **Reinforcement Learning (RL)**, explorant différentes approches et algorithmes appliqués à des environnements variés.

Chaque TP est conçu pour offrir une compréhension progressive des concepts clés du RL, en passant de l'exploration d'environnements simples à des techniques avancées comme **Policy Gradient**.

---

## 📂 Contenu des TPs

### 🏗 TP1 : Découverte de Gymnasium et CartPole
- **Fichier** : `TP1.ipynb`
- **Objectif** : Prise en main de l'environnement **CartPole-v1** via Gymnasium.
- **Concepts abordés** :
  - Initialisation de l’environnement et exploration des espaces d’actions et d’observations.
  - Exécution d'actions aléatoires et analyse des récompenses et états.
  - Interaction manuelle pour comprendre la dynamique du système.

### ❄ TP2 : Q-Learning sur FrozenLake
- **Fichier** : `TP2.ipynb`
- **Objectif** : Implémenter **Q-Learning** pour résoudre l’environnement **FrozenLake**.
- **Concepts abordés** :
  - Création et initialisation d'une **Q-table**.
  - Entraînement d’un agent avec Q-Learning (réglage des hyperparamètres **alpha, gamma, epsilon**).
  - Évaluation des performances avec affichage du taux de réussite.

### 🚦 TP3 : Q-Learning vs SARSA sur un Environnement de Trafic
- **Fichier** : `TP3.ipynb`
- **Objectif** : Comparer **Q-Learning** et **SARSA** sur un environnement personnalisé de gestion du trafic.
- **Concepts abordés** :
  - Initialisation de **TrafficEnvironment**.
  - Implémentation des deux algorithmes avec des paramètres similaires.
  - Comparaison des performances via des **courbes de récompenses**.

### 🚖 TP4 : Policy Gradient (PPO) sur Taxi-v3
- **Fichier** : `TP4.ipynb`
- **Objectif** : Entraîner un agent avec **PPO (Proximal Policy Optimization)** sur **Taxi-v3**.
- **Concepts abordés** :
  - Mise en place d’une **politique** et de valeurs associées.
  - Optimisation avec PPO (incluant **reward shaping** et **clipping**).
  - Évaluation des performances après entraînement.

---

## 🛠 Prérequis

- **Python 3.9+**
- Bibliothèques requises :
  ```bash
  pip install gymnasium numpy matplotlib traffic_env
  ```

---

## 🚀 Utilisation

Exécutez les notebooks dans l'ordre **TP1 → TP4** pour une progression logique des concepts.
Chaque TP est commenté pour faciliter la compréhension et l'expérimentation.

---

## ✍️ Auteur

**BOURI Souhail**

📌 *N'hésitez pas à contribuer ou signaler des améliorations !* 🚀

