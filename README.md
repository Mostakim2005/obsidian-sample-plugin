# Obsidian Template — Mostakim2005

Personal template for Obsidian community plugins by **Mostakim2005** (`Mostakim 4 Argon`).

Ships with PolyForm Noncommercial 1.0.0 (code) + CC BY-NC 4.0 (docs) by default — free non-commercial use with credit, no commercial use. Not OSI open-source.

## How to reuse for a new plugin

1. Click **Use this template** → create repo
2. Rename: `manifest.json` `id` + `name`, regex-replace `sample-plugin` with your ID
3. Update `package.json` `name`, `description`, `keywords`
4. Replace `src/main.ts` + add `src/settings.ts` as needed (example: `src/main.ts` in this repo)
5. Replace `styles.css` with your styles
6. Bump `manifest.json` `version` → update `versions.json` → `npm run build` → GitHub release with `main.js`, `manifest.json`, `styles.css`

## Develop

- `npm i` (Node 18+)
- `npm run dev` — watch mode
- `npm run build` — production bundle
- `npm run lint` — ESLint + obsidianmd plugin

Manual install: copy `main.js`, `manifest.json`, `styles.css` to `<Vault>/.obsidian/plugins/<plugin-id>/`.

## License

Code: PolyForm Noncommercial 1.0.0 (see `LICENSE`). Docs: CC BY-NC 4.0. Copyright © Mostakim2005.

Full legal text: https://www.polyformproject.org/licenses/noncommercial/1.0.0
