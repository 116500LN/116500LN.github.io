---
layout: single
title: "Guide"
permalink: /guide/
author_profile: true
---

Si vous voyez l'image ci-dessous, le fichier avatar est bien déployé :

![Avatar](/images/profile.png)

Si l'image **n'apparaît pas**, vérifiez :
1. Que ce fichier existe dans votre dépôt : `images/profile.png`.
2. Que la build GitHub Pages est terminée (onglet *Actions* → `pages-build-deployment` vert).
3. Rechargez la page avec **Ctrl+F5**.

Pour afficher l'avatar aussi dans la barre latérale, vérifiez dans `_config.yml` :
```yaml
author:
  avatar: "profile.png"
```
