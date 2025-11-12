# Final Visual Stabilize Patch

This patch fixes the failed build and restores the full theme styling by replacing `_includes/head.html`
with a **safe** version that:
- uses `{% seo %}` (jekyll-seo-tag) instead of including `head/seo.html` (which can 404 in some setups),
- loads the theme CSS: `/assets/main.css` and `/assets/css/main.css`,
- keeps your custom head include (`head/custom.html`).

It also **keeps** the top navbar and footer **removed** (`_includes/masthead.html` and `_includes/footer.html` are empty),
and adds a tiny CSS to make the left sidebar sticky.

## Install
1) GitHub → Add file → Upload files → upload the **contents** of this ZIP at the **repo root** (preserve folders).
2) Accept replacements → Commit → Actions build should turn green → Hard refresh the site.

If build still fails, open the failing job → *Details* → copy the first 20 lines of the error; but this patch should fix the
typical `Could not locate the included file 'head/seo.html'` and missing CSS issues.
