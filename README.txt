# Pack "clean / vierge" (AcademicPages)

Ce pack remplace l'affichage par une page d'accueil vide et deux pages minimales (À propos, CV).
Il **n'ajoute aucune publication, aucun post, aucune entrée de collections**.

## Déploiement
1. Ouvrez le dépôt `116500LN/116500LN.github.io` sur GitHub.
2. **Supprimez** le contenu des dossiers suivants s'ils existent, pour repartir de zéro :
   - `_posts/*`
   - `_publications/*`
   - `_talks/*`
   - `_teaching/*`
   - `_portfolio/*`
   - `files/*` (vous pourrez garder votre CV si vous en avez un)
3. Cliquez **Add file → Upload files** et uploadez le contenu de ce pack à la **racine** du dépôt.
4. `Commit changes`.
5. Vérifiez l'onglet **Actions** (workflow `pages-build-deployment` en vert), puis rechargez `https://116500ln.github.io/` (Ctrl+F5).

## Ajouts futurs
- Ajoutez vos PDF dans `files/`.
- Créez de nouvelles pages dans `_pages/`.
- Réactivez les collections quand vous voudrez en créant les dossiers correspondants (`_publications`, etc.).
