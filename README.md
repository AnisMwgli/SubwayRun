# 🚆 SubwayRun

SubwayRun est un mini-jeu d’arcade inspiré de Subway Surfers. Le joueur court automatiquement dans un tunnel composé de **3 voies** et doit éviter les obstacles en changeant de voie. Le but est de survivre le plus longtemps possible tout en accumulant un score basé sur la distance parcourue et les bonus collectés.

---

## 🎮 Fonctionnalités

- 🛤️ Trois voies verticales en perspective
- 🎮 Déplacements gauche/droite
- ⚠️ Obstacles générés aléatoirement
- 🪙 Bonus à collecter
- 🚀 Vitesse progressive selon le temps
- 📈 Score basé sur la distance + bonus
- 💥 Game Over en cas de collision

---

## 🧰 Technologies utilisées

- **React.js** (structure du jeu)
- **Vite** (environnement de développement)
- **Context API** (gestion de l’état global)
- **Framer Motion** (animations fluides)
- **CSS transform + perspective** (effet 3D simple)

---

## 📦 Installation

Clone le projet :

```bash
git clone https://github.com/<ton-user>/SubwayRun
cd SubwayRun
```

Installe les dépendances :
```bash
npm install
```
Lancer le jeu en local :
```bah
npm run dev
```

---

## 📂 Structure du projet
```
src/
  components/
    Player.jsx
    Obstacle.jsx
    Lane.jsx
    Coin.jsx
    Score.jsx
    GameOver.jsx
  context/
    GameContext.jsx
  hooks/
    useGameLoop.js
  assets/
  App.jsx
  main.jsx
```

---

## 🕹️ Gameplay

Contrôles :
```
←  Déplacer à gauche
→  Déplacer à droite
```

Objectif :
Éviter les obstacles, collecter les bonus, et tenir le plus longtemps possible pour améliorer son score.

---

## 🚀 Améliorations futures

- Ajout du saut et de la glissade
- Nouveaux types d’obstacles
- Multiplicateurs de score
- Skins du personnage
- Changement d’environnement (jour/nuit, ville, métro…)
- Son & effets audio

---

## 👥 Crédits

Projet réalisé dans un cadre pédagogique.
Développé par : Anis, Aymen, Jean Julien 

## 📜 Licence

Ce projet est libre d’utilisation à des fins personnelles ou éducatives.
