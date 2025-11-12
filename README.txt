# Patch: home cleanup + sidebar text + remove footer

Files:
- `index.html` — clears home body text (keeps only the title "Accueil").
- `_config.yml` — sidebar: bio="some maths stuff", location="Paris, France - Geneva, Switzerland", employer="BSc in maths at Sorbonne".
- `_includes/footer.html` — empty to remove the site footer (theme include override).

Install:
1) GitHub → Add file → Upload files.
2) Upload the **contents** of this ZIP at the **repository root** (preserving folders).
3) Accept replacements → Commit → check Actions → hard refresh the site.
