# ⚡ WordZap — Le Jeu de Frappe Ultime en Français

![WordZap Banner](https://img.shields.io/badge/Status-Active-brightgreen) ![HTML5](https://img.shields.io/badge/Frontend-HTML5%20%7C%20CSS3%20%7C%20JS-orange) ![PWA](https://img.shields.io/badge/PWA-Ready-blue) ![License](https://img.shields.io/badge/License-MIT-green)

**WordZap** est un jeu de dactylographie arcade rapide, immersif et stimulant, entièrement conçu en Français. Testez vos réflexes, améliorez votre vitesse de frappe (WPM) et tranchez des milliers de mots tirés du dictionnaire grâce à des effets visuels néon et une bande-son dynamique.

---

## ✨ Fonctionnalités Principales

* 📚 **Dictionnaire Géant (330 000+ mots)** : Intégration du grand dictionnaire de la langue française pour une variété infinie sans répétition.
* 🔀 **Variété Grammaticale** : Alternance intelligente entre **noms**, **adjectifs**, **verbes** et vocabulaire général.
* 🎮 **4 Modes de Jeu** :
  * **Classique** : 5 Vies pour faire le meilleur score possible.
  * **Sprint Chrono 60s** : Tapez le maximum de mots en 1 minute.
  * **Mort Subite** : La moindre faute de frappe met fin à la partie !
  * **Mode Zen** : Entraînement libre sans stress ni limite de temps.
* ⚡ **Système de Power-ups** :
  * 🛡️ **Bouclier** (Touche `1`) : Absorbe la prochaine erreur.
  * ❄️ **Gel du Chrono** (Touche `2`) : Interrompt le timer pendant 5 secondes.
  * 💣 **Zap Bomb** (Touche `3`) : Tranche instantanément le mot actuel.
  * ⚡ **Double Score 2x** (Touche `4`) : Doubler vos points pendant 10 secondes.
* 📊 **Statistiques & Historique Découplés** : Filtrez vos performances (WPM, précision, combos, durée moyenne) par mode de jeu et niveau de difficulté.
* 🎨 **Thèmes Visuels Dynamiques** : Basculez en un clic entre *Neon Rose*, *Cyberpunk Gold*, *Matrix Green*, et *Synthwave Sunset*.
* 🌐 **Mode Offline First & PWA** :
  * Sauvegarde locale du dictionnaire et de l'état de la partie interrompue (`localStorage`).
  * Installable directement sur l'écran d'accueil (Mobile & PC) sans passer par le navigateur.

---

## 🚀 Installation & Lancement

Ce projet est un projet web autonome (*Single Page Application*). Aucun framework lourd ni serveur Node.js n'est nécessaire !

### Option 1 : Utilisation directe (Local)
1. Clonez ce dépôt GitHub :
   ```bash
   git clone [https://github.com/Franckemery/WordZap.git](https://github.com/Franckemery/WordZap.git)

Ouvrez le fichier index.html directement dans votre navigateur web.

### Option 2 : Déploiement en ligne
- Vous pouvez héberger le projet gratuitement en quelques secondes sur :

- GitHub Pages (Réglez la branche main dans les Settings > Pages de votre dépôt).

- Netlify Drop (Glissez-déposez le dossier contenant index.html).

- Vercel / Render.

## 🎮 Comment Jouer ?
- Choisissez votre Mode de Jeu, votre Difficulté et la Longueur des Mots.

- Saisissez les mots affichés au centre de l'écran aussi vite et précisément que possible.

- Chaque mot complété augmente votre score et votre Combo.

- Activez vos Bonus/Power-ups accumulés grâce aux raccourcis clavier (1, 2, 3, 4) pour prolonger votre partie.

## 🛠️ Technologies Utilisées
- HTML5 : Structure de l'application & balises PWA Manifest.

- CSS3 : Animations d'aurore, reflets néon (shimmer), grilles adaptatives et effets de particules.

- JavaScript (Vanilla ES6+) : Gestion du jeu, calcul du WPM, algorithmes de filtrage de dictionnaire, audio-synthétiseur Web Audio API.

- Service Worker & LocalStorage : Mémorisation locale des données et fonctionnement 100% hors-ligne.

## 📄 Licence
Ce projet est distribué sous la licence MIT. Vous êtes libre de le réutiliser, le modifier et le distribuer.
