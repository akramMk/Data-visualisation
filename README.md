# Campus Nav - Deux Vues
Lien vers document de suivi : https://docs.google.com/document/d/1KnvpVF77lk8MRJoJ6NbbofBQT2zmNtjzE8HE51qbv6Q/edit?usp=sharing
Lien vers document de cadrage : https://docs.google.com/document/d/1deJoQGPyFI59a5WHeeROuHtaMHOaKDnYynUkL6Yc8dA/edit?usp=sharing
**Campus Nav** est une application web interactive qui permet de naviguer et d'explorer les établissements et les stations de vélos sur un campus. L'application propose deux vues principales : une vue **Compass** pour la navigation et une vue **Explorer** pour l'analyse des données.

## Fonctionnalités

- **Vue Compass** :
  - Carte interactive avec les établissements du campus.
  - Sélection d'un établissement pour accéder à la vue Explorer.
  - Affichage des stations de vélos à proximité.

- **Vue Explorer** :
  - Statistiques et visualisations des données de vélos.
  - Filtres dynamiques (date, heure, distance).
  - Graphiques interactifs (barres, lignes, nuages de points, etc.).
  - Carte de chaleur pour visualiser l'utilisation des stations.

## Technologies utilisées

- **Frontend** :
  - [Leaflet](https://leafletjs.com/) pour les cartes interactives.
  - [D3.js](https://d3js.org/) pour les visualisations de données.
  - [Tailwind CSS](https://tailwindcss.com/) pour le style et la mise en page.

- **Données** :
  - Données des établissements au format GeoJSON.
  - Données des stations de vélos au format CSV.

## Installation

1. **Cloner le dépôt** :
   ```bash
   git clone https://forge.univ-lyon1.fr/p2312961/data-vis-2024.git