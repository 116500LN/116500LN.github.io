# Visual Fix Patch — restore theme styling + left menu only

This patch fixes the "unstyled" pages by restoring a proper `_includes/head.html` that loads the theme CSS,
keeps the top navbar removed and footer removed, and keeps the left docs-style menu everywhere.
It also ensures only the requested sections exist (Blog, Career Design, Personal Projects, Miscellaneous, CV).

## What to upload
- `_includes/head.html` (restores CSS)
- `_includes/masthead.html` (empty; no top bar)
- `_includes/footer.html` (empty; no footer)
- `_includes/head/custom.html` and `assets/css/custom-fix.css` (optional sticky sidebar)
- `_data/navigation.yml` (docs-only menu with the requested sections)
- `_pages/*.md` (fresh stubs with `sidebar.nav: docs`)
- `index.html` (title only; inherits left nav)

## Optional: merge defaults
If your `_config.yml` doesn't already set the docs sidebar globally, add this block to the end of it:
```
defaults:
  - scope: { path: "", type: pages }
    values:
      sidebar:
        nav: "docs"
  - scope: { path: "", type: posts }
    values:
      sidebar:
        nav: "docs"
```
(We ship it as `_config.defaults.only.yml` so you can copy/paste without overwriting your other settings.)

## Install
1) GitHub → **Add file → Upload files** → upload the **contents** of this ZIP at the **repo root** (preserve folders).
2) Accept replacements → Commit → **Actions** build → **Ctrl+F5** on the site.
3) Test `/cv/` and the other sections; they should be fully styled, with only the left menu.

If any page is still unstyled, it's likely `_includes/head.html` wasn't replaced or the CSS path is blocked.
