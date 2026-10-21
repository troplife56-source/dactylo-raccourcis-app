# ⌨️ Application de Dactylographie & Raccourcis Pro

Application web interactive et multilingue conçue pour s'entraîner à la dactylographie, maîtriser les raccourcis clavier essentiels et apprendre les bonnes postures ergonomiques.

## 🚀 Fonctionnalités Principales

* **🎯 Mode Entraînement de Frappe (Aléatoire & Infini) :** Génération dynamique de séquences de caractères pour s'entraîner sans limite sur toutes les lettres du clavier.
* **⚡ Entraînement aux Raccourcis :** Un mode interactif pour tester et valider vos compétences sur les raccourcis clavier les plus utiles.
* **📚 Bibliothèque de Raccourcis Complète :** Une liste riche et catégorisée regroupant les raccourcis d'édition, de navigation et de système.
* **🌐 Multilingue :** Prend en charge trois dispositions de clavier majeures :
  * **AZERTY (FR)**
  * **QWERTY (US)**
  * **Arabe (Standard & Tachkil)**
* **🔊 Retours Sonores :** Effets audios discrets (clic de réussite et son d'erreur) pour une immersion optimale.
* **📖 Guide & Posture Ergonomique :** Une section dédiée aux principes de la frappe à l'aveugle, illustrée avec des visuels pour le positionnement des mains et le respect de la ligne de repos (*Home Row*).

---

## 🛠️ Technologies Utilisées

* **HTML5** (Structure sémantique et composants visuels)
* **CSS3** (Design moderne, mode sombre et grille responsive)
* **JavaScript (Vanilla)** (Gestion de la logique interactive, des dispositions, des sons et du générateur aléatoire)

---

## 📂 Structure du Projet

```text
├── index.html        # Fichier unique contenant toute la structure et la logique
├── sonde/            # Dossier contenant les fichiers audio
│   ├── clic.mp3
│   └── error.mp3
└── images/           # Dossier contenant les visuels de posture
    ├── azerty-guide.jpg
    ├── qwerty-guide.jpg
    └── arabic-guide.jpg
