# Perpignan 3D Studio

Outil web qui modélise Perpignan en 3D à partir de données ouvertes et l'exporte en tuiles GLB pour un moteur de jeu (Unity, Unreal, Godot, Three.js, Blender).

## Utilisation
1. Ouvrir la page GitHub Pages du dépôt dans Safari ou Chrome.
2. **Carte** : choisir un quartier ou toucher des tuiles.
3. **Générer la sélection en 3D**, puis **Modèle 3D** pour la voir.
4. **▶ Jouer** pour conduire (joystick tactile, ou ZQSD au clavier ; F = à pied).
5. **Export** : GLB de la zone ou ZIP par tuiles (avec manifeste, réseau routier et prompt pour Claude Code).

Le bouton **🩺 Diagnostic** vérifie la carte, le WebGL, l'accès à l'IGN, à OpenStreetMap et au moteur 3D.

## Mise à jour
Remplacer `index.html` dans le dépôt (Add file › Upload files). L'adresse ne change pas.

## Données et mentions obligatoires
- Bâtiments BD TOPO® et orthophotographies : © IGN — Licence Ouverte Etalab 2.0
- Voies, eau, arbres, points d'intérêt : © contributeurs OpenStreetMap — ODbL 1.0
- Relief : Terrain Tiles (AWS Open Data / Mapzen), sources dont EU-DEM (Copernicus) et SRTM
- Bibliothèques : MapLibre GL JS et Three.js (chargées depuis cdn.jsdelivr.net)
