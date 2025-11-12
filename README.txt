# Blog Visual Fix Patch

This patch fixes the "unstyled /blog/" problem by:
- Restoring a safe `_includes/head.html` that loads the theme CSS (`/assets/main.css`) and SEO,
- Keeping the top navbar and footer removed,
- Ensuring a left docs menu exists and a minimal `/blog/` page with a visible OK marker,
- Making sure `_pages` is included and `url:` points to your domain.

## Install
1) GitHub → Add file → Upload files → upload the **contents** of this ZIP at the **repo root** (preserve folders).
2) Accept replacements → Commit → check **Actions** build → hard refresh `/blog/`.

You should see: **“Blog OK ✅ — styles loaded.”** at the top and proper site styling.
