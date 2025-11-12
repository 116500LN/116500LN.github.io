# Patch: Replace sections (keep only CV + Blog/Career Design/Personal Projects/Miscellaneous)

This patch:
- Updates the left menu to only show: Blog, Career Design, Personal Projects, Miscellaneous, CV.
- Adds minimal pages for these new sections in `_pages/`.
- Unpublishes previous sections (Publications, Talks, Teaching, Portfolio, Guide) so they disappear (no URLs built).
- Keeps the left-menu-only layout (masthead removed, footer removed).

## Install
1) GitHub → Add file → Upload files.
2) Upload the **contents** of this ZIP at the **repository root** (keep folders).
3) Accept replacements → Commit → Actions build → Hard refresh (Ctrl+F5).

If you want me to also delete the old files physically from the repo, say the word and I’ll send a "cleanup" patch with `git rm` instructions you can follow via the UI.
