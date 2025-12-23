# Tulip Forest

This is the "鬱金香之森" static site. It includes PWA/Apple meta tweaks and mobile drag-and-drop polyfill for iOS.

Important steps to publish to GitHub:

1. Create a new repository on GitHub (e.g. `tulip-forest`).
2. On your machine, in this project folder run:

```bash
git remote add origin https://github.com/<your-username>/tulip-forest.git
git push -u origin main
```

3. Upload `icon-192.png` and `icon-512.png` into the repository root (they are required by `manifest.json` and Apple touch icon). If you previously added the site to your iPhone home screen, delete the old shortcut and re-add after these files are present.

Notes:
- If you want me to push the repo for you, I need GitHub access (gh CLI auth or a personal access token). I can provide exact `gh` commands to run here if you prefer.
- The project already initializes a local git repo and includes a first commit.
