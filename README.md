# Tree site

- `index.html` — the site (self-contained).
- `content.md` — the tree. Edit this file; indent 2 spaces per level. `# Heading` = root node, `[Label](url)` = link.

## Publish on GitHub Pages

1. Create a repo and upload `index.html` and `content.md` to the root.
2. Settings → Pages → Source: "Deploy from a branch" → `main` / `(root)` → Save.
3. Open `https://<user>.github.io/<repo>/` after ~1 minute.

Edits to `content.md` go live on the next Pages build.
