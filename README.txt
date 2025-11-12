This patch fixes all current issues observed on https://116500ln.github.io/:
- Wrong absolute links pointing to academicpages.github.io -> sets site.url to your domain.
- Default placeholders (name, bio, etc.) -> replaced with your values.
- Enforces left docs-style sidebar everywhere; removes top navbar and footer.
- Keeps only the sections: Blog, Career Design, Personal Projects, Miscellaneous, CV.
- Ensures _pages is included and index page is minimal.
- Ships images/profile.png (400x400) for the avatar.

Install:
1) Upload the contents of this ZIP at the repo root (preserve folders).
2) Accept replacements; Commit; check Actions build; hard refresh the site.
