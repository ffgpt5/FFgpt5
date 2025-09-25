# FFgpt5 Kodi Repository

This is a GitHub-hosted Kodi repository. Upload the contents of the `repo/` folder to your GitHub repository (branch: `main` or `gh-pages`) and point the repository add-on to the `BASE_URL` below.

## Files
- `addons.xml` and `addons.xml.md5` at repo root
- `zips/` contains packaged add-ons:
  - `script.module.ptw-2025.08.17.zip`
  - `plugin.video.smr_link_tester-1.1.16.zip`

## Repository Add-on
Use `repository.ffgpt5-1.0.0.zip` to install the repo in Kodi. Before you publish, edit `repository_addon/repository.ffgpt5/addon.xml` and replace `{BASE_URL}` with one of:

- **GitHub Pages** (recommended): `https://<USER>.github.io/<REPO>`
- **Raw GitHub** (for main branch): `https://raw.githubusercontent.com/<USER>/<REPO>/main`

Make sure those URLs serve:
- `addons.xml` → `<BASE_URL>/addons.xml`
- `addons.xml.md5` → `<BASE_URL>/addons.xml.md5`
- `zips/` → `<BASE_URL>/zips/`

