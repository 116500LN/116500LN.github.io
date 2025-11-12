# Patch: Left menu only (replace top navbar) + US sidebar text kept

This patch:
- **Removes the horizontal top navbar** (empty `_includes/masthead.html`).
- **Shows the docs-style left menu on EVERY page** via `_config.yml` defaults and `_data/navigation.yml` (`docs:` list).
- Keeps your sidebar text (bio/location/employer) and footer removal.
- Adds small CSS to make the left sidebar sticky and remove extra top spacing.

## Install
1) GitHub → Add file → Upload files.
2) Upload the **contents** of this ZIP at the **repository root** (preserving folders).
3) Accept replacements → Commit → Actions build → Hard refresh (Ctrl+F5).

If any page still shows a top bar, that page likely has a custom layout overriding `masthead`. Send me its path and I’ll patch it.
