# Revue de l'inventaire des aires de stationnement

Outil de travail de **Carte 42** pour le marché 2026-03 de l'EPTB Vistre Vistrenque
(étude de l'exposition aux inondations des aires de stationnement publiques de surface,
action 1.9 du PAPI 3 Vistre).

Ce dépôt ne contient que l'interface compilée et l'inventaire provisoire qu'elle affiche.
**Les résultats présentés ici sont des données de travail, non validées par le maître
d'ouvrage.** Ils n'engagent ni l'EPTB Vistre Vistrenque ni aucune autre collectivité.

Sources de l'inventaire : OpenStreetMap, BD TOPO IGN, cadastre Etalab, fichier DGFiP des
parcelles des personnes morales. Le code de production, les décisions de méthode et les
livrables sont tenus dans un dépôt privé.

## Contenu

- `index.html`, `assets/` — l'interface, compilée depuis le dépôt de production.
- `donnees/aires.geojson` — inventaire provisoire des aires et repères sans emprise.
- `donnees/etat.json` — communes et compteurs.
- `revue/` — décisions prises à l'écran, un fichier par commune.
