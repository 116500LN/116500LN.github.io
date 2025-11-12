# Patch: avatar + page Guide (test)

Contenu:
- `images/profile.png` (PNG 400x400)
- `_pages/guide.md` (page de test affichant l'image)

Installation:
1) Sur GitHub → **Add file → Upload files**.
2) **Déposez le *contenu* de ce ZIP** à la racine du dépôt (ne chargez pas le ZIP tel quel). Acceptez de remplacer `images/profile.png` s'il existe.
3) Commit → vérifiez `Actions` (build verte) → ouvrez `/guide/` et `Ctrl+F5`.

Si l'image apparaît sur `/guide/` mais pas dans la barre latérale, ajoutez dans `_config.yml` :
  author:
    avatar: "profile.png"
