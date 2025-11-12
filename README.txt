# Minimal Ready Pack — AcademicPages (sections vides, home propre)

**Objectif** : 
- Toutes les sections restent cliquables (Publications, Talks, Teaching, Portfolio, Blog, CV).
- La page d’accueil **ne** montre **aucun** tutoriel du template.
- Aucun contenu listé (sections vides), site prêt pour vos ajouts.

## Fichiers à déposer (remplacement recommandé)
- `index.html` (remplace la home du template)
- `_data/navigation.yml`
- `_pages/*.md` (stubs vides)
- `_config.yml` (minimal, personnalisé)
- `scripts/clean_sections.sh` (optionnel)

## Procédure (UI GitHub)
1. Ouvrez `116500LN/116500LN.github.io` → **Add file → Upload files**.
2. Déposez **tout le contenu** de ce dossier à la racine. Acceptez de **remplacer** les fichiers existants.
3. (Optionnel) Supprimez les anciens items des collections : `_publications/*`, `_talks/*`, `_teaching/*`, `_portfolio/*`, `_posts/*`.
4. **Commit changes** → Vérifiez **Actions** (workflow `pages-build-deployment` en vert) → Hard refresh du site.

## Procédure (ligne de commande)
```bash
# À la racine du dépôt cloné
bash scripts/clean_sections.sh
git add -A && git commit -m "Clean sections (empty stubs)" && git push
```
