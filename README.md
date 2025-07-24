# 📦 Projet de Prototype avec Simulation et Code Arduino

Ce fichier ZIP contient l'ensemble des éléments du projet, incluant :

## 📝 Contenu du fichier ZIP

- **Rapport du projet** (`rapport ppp iia4 .pdf` ou similaire) : une description détaillée de la démarche, des résultats et des conclusions.
- **Images du prototype réel** : photos du montage physique réalisé.
- **Projet de simulation sous ISIS/Proteus** (`/simulation_isis/`) : fichiers `.DSN` ou autres nécessaires à l'ouverture de la simulation.
- **Code Arduino**  :
  - Code pour le prototype physique
  - Code adapté à la simulation
- **Images des résultats de la simulation** (`/images_simulation/`) : captures montrant le fonctionnement attendu.

## ⚠️ Astuce importante (Module GSM)

Lors de l'utilisation du **module GSM**, **ajouter un condensateur de 1000 μF en parallèle avec le module** est fortement recommandé.  
Ce composant permet :
- De **stabiliser l’alimentation**
- De **fournir un courant suffisant pendant les pics de consommation** du module, notamment lors de l’émission d’un signal.

Sans ce condensateur, le module GSM peut ne pas fonctionner correctement, redémarrer de manière aléatoire, ou échouer à envoyer des SMS.



