# ZIP — Sections 'lorem ipsum' + Nom = "G B"

Ce pack :
- crée/écrase les pages de section (Publications, Talks, Teaching, Portfolio, Blog Posts, CV, Guide) pour éviter les 404 et afficher "lorem ipsum",
- met à jour le nom global en "G B",
- règle la localisation : "Paris, France · Geneva, Switzerland",
- ajoute "BS maths Sorbonne University" sur la page d'accueil.

## Installation
1. Dans `116500LN/116500LN.github.io`, cliquez **Add file → Upload files**.
2. Déposez le **contenu** de ce ZIP à la **racine** du dépôt (acceptez de remplacer).
3. **Commit changes** puis vérifiez **Actions → pages-build-deployment** (vert).
4. Hard refresh sur `https://116500ln.github.io/` (Ctrl+F5).

## Notes
- Les pages utilisent `layout: single` → pas d'agrégation automatique de collections.
- Le menu est dans `_data/navigation.yml` et correspond à la capture (ordre et libellés).

