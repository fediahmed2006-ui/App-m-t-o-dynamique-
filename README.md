# App-meteo-dynamique-


App Météo – Fedi Ahmed


Description du projet
Cette application météo permet de rechercher la météo actuelle d’une ville, d’afficher plusieurs cartes météo, de sauvegarder les villes choisies localement et de récupérer automatiquement la météo de votre position.
Il s’agit d’un projet Web complet utilisant HTML, CSS et JavaScript, avec interaction temps réel via l’API OpenWeatherMap.
Technologies utilisées
HTML5 — Structure de l’application
CSS3 — Design moderne, effet glassmorphism, responsive
JavaScript ES6+ — Logique, API, DOM
OpenWeatherMap API — Récupération des données météo
LocalStorage — Sauvegarde des villes
Geolocation API — Récupération de la météo selon la position réelle
Git & GitHub — Versioning, documentation et hébergement


Fonctionnalités principales
Recherche météo par nom de ville
Affichage sous forme de cartes météo dynamiques
Météo selon la géolocalisation
Suppression d’une carte en cliquant dessus
Sauvegarde automatique des villes dans localStorage
Restauration des villes au rechargement
Thème visuel automatique selon la météo (clear, clouds, rain...)
Interface moderne, fluide et responsive


Lien vers la page Github pages
https://fediahmed2006-ui.github.io/App-meteo-dynamique-/



Nouveautés explorées / Ce que j'ai appris
Manipuler une API REST (fetch, JSON, erreurs HTTP)
Construire une interface dynamique avec JavaScript (DOM, events)
Utiliser localStorage pour sauvegarder des données persistantes
Utiliser l'API de géolocalisation du navigateur
Créer un design moderne (glassmorphism, variables CSS, responsive grid)
Gérer les classes dynamiques selon les conditions météo
Comprendre la logique de versioning avec Git & GitHub


Difficultés rencontrées
Problèmes avec l'appel API OpenWeatherMap (erreurs 401, mauvais paramètre)
Gestion d’erreurs si la ville est incorrecte ou inexistante
CSS blurred background qui se superposait mal
Problème de mise à jour des cartes déjà affichées
Gestion du localStorage et conversions JSON
Fonctionnement parfois instable de la géolocalisation


Solutions apportées
Vérification des réponses API et affichage d’erreurs claires
Utilisation de try...catch et resp.ok pour assurer une récupération propre
Ajout d’un fond fixé via body::before + filtre blur pour un rendu propre
Détection et remplacement des cartes existantes via dataset.city
Gestion JSON avec JSON.stringify() et JSON.parse() sécurisée
Vérification du support de la géolocalisation + gestion des permissions refusées
Organisation du code en fonctions claires : fetchWeatherByCity, addCity, createCard, etc.
