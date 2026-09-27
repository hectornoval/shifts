# Tree site

- `index.html` — the site (self-contained).
- `content.md` — the tree. Edit this file; indent 2 spaces per level. `# Heading` = root node, `[Label](url)` = link.

## Publish on GitHub Pages

1. Create a repo and upload `index.html` and `content.md` to the root.
2. Settings → Pages → Source: "Deploy from a branch" → `main` / `(root)` → Save.
3. Open `https://<user>.github.io/<repo>/` after ~1 minute.

## Linking to other .md files

`- [Filter](filter.md)` — clicking opens `filter.md` as its own tree (URL becomes `?src=filter.md`).
Works with files in subfolders (`docs/filter.md`) or any raw GitHub URL.

## Navigation bar

Edit `nav.md` — one link per bullet: `- [Filter](docs/filter.md)`. Links above the `---` line sit on the left, links below it on the right. Delete the file to hide the bar.

## Breadcrumb

Appears automatically on every linked page and grows as you go deeper (`Table / Filter / Dropdown`). Each crumb uses the file's `# Heading`. Nothing to add in the .md files.

Edits to `content.md` go live on the next Pages build.
