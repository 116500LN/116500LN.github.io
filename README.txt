# Pack clé-en-main (AcademicPages)

Fichiers inclus à déposer dans votre dépôt `116500LN/116500LN.github.io` :
- `_config.yml` (config personnalisée)
- `_data/navigation.yml` (menu minimal)
- `_pages/about.md`
- `_pages/cv.md`
- `_publications/2025-vitali.md`
- `files/` (mettez ici vos PDF : `CV_Gianni_Blaising.pdf`, `vitali_note.pdf`, etc.)

## Déploiement
1. Ouvrez votre dépôt sur GitHub.
2. Uploadez tout le contenu de ce dossier (ou remplacez les fichiers existants).
3. Vérifiez l’onglet **Actions** → workflow `pages-build-deployment` doit passer au vert.
4. Actualisez `https://116500ln.github.io/` (hard refresh).

## Personnalisation rapide
- Changez la bio dans `_config.yml` → `author.bio`.
- Remplacez/ajoutez des éléments du menu dans `_data/navigation.yml`.
- Ajoutez des publications dans `_publications/` (un fichier `.md` par item, même schéma que l’exemple).
- Déposez vos fichiers PDF dans `files/` et mettez à jour les liens `paperurl`/`CV`.
