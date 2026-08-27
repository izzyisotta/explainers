# Explainers

Outward-facing explainer pages, served by GitHub Pages at https://izzyisotta.github.io/explainers/

- `src/*.yaml` is the source; each `*.html` at the root is rendered from it with the vault's `render-det` skill. Never hand-edit the HTML.
- Render: `python3 "$VAULT/02 Skills, Agents & Templates/Skills/render-det/render.py" src/<name>.yaml -o <name>.html`, then add a row to `index.html` if new, commit, push.
- This repo is PUBLIC. Only non-sensitive documents go here.
