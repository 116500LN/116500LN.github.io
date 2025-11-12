# Avatar Patch — AcademicPages

This patch adds your avatar at `images/profile.png` (PNG, 400x400).
Minimal Mistakes/AcademicPages expects `author.avatar: "profile.png"` in `_config.yml`
and reads it from the `images/` folder.

## Install
1. Open `116500LN/116500LN.github.io` on GitHub → **Add file → Upload files**.
2. Upload the contents of this ZIP at the repository root (it will create/replace `images/profile.png`). Accept replacement if prompted.
3. Commit. Then open the site and hard refresh (Ctrl+F5).

## If avatar doesn't show
- Ensure `_config.yml` contains:
  author:
    avatar: "profile.png"
- Clear cache or wait for the Pages build to finish (Actions → pages-build-deployment).
