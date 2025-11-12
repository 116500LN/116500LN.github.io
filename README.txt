# All-in-one Fix for 116500ln.github.io

This patch:
- Corrects `_config.yml` (`url`, includes, plugins, defaults) and keeps left docs menu everywhere,
- Restores theme styling with a safe `_includes/head.html` (loads `/assets/main.css` + `{% seo %}`),
- Removes the top navbar and footer (empty includes),
- Keeps only the sections Blog, Career Design, Personal Projects, Miscellaneous, CV,
- Ensures `_pages` is included, provides a minimal home, avatar image, and a `/debug/` page.

## Install
1) GitHub → **Add file → Upload files** → upload the **contents** of this ZIP at the **repo root** (preserve folders).
2) Accept replacements → Commit → open **Actions** (build should turn green) → hard refresh the site.
3) Visit `/debug/` to verify `site.url`, CSS links, and the docs nav.

## Notes
If you still see old sections, they are legacy files in your repo. Delete them via the UI (open file → Delete → Commit), or ask me for a cleanup patch that removes them safely.
