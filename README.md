# Your kriti website

Three files:

- `index.html`  – the public site (you never edit this)
- `data.json`   – all your content (site details + every work)
- `admin.html`  – a private-ish editor that edits `data.json` for you

## One-time setup (free, about 10 minutes, works from a phone)

1. Create a free account at github.com and make a **new public repository** (e.g. `kritis`).
2. Upload all three files (Add file → Upload files).
3. Repo **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` / root → Save.
4. After a minute your site is live at `https://<username>.github.io/kritis/`
   and your editor is at `https://<username>.github.io/kritis/admin.html`.

## Let the editor publish for you (recommended)

1. GitHub → Settings → Developer settings → Personal access tokens → **Fine-grained tokens** → Generate.
2. Repository access: *Only select repositories* → your `kritis` repo.
3. Permissions → Repository permissions → **Contents: Read and write**. Generate and copy the token.
4. Open `admin.html` → "GitHub connection" → enter username, repo, branch (`main`), path (`data.json`), token → Save connection.

The token stays only in that browser. Never paste it anywhere else.

## Everyday use

1. Open `admin.html`.
2. Tap **+ New work**, fill the form (blank line between charanas), **Save work**.
3. Tap **Publish to GitHub**. The site updates in about a minute.

No GitHub token? Tap **Download data.json** instead, then upload it to the repo to replace the old one.

## Notes

- Unpublished edits are kept on your device, so nothing is lost if you close the tab.
- `admin.html` is public but cannot change anything without your token. To hide it, rename it to something private (e.g. `edit-7x2k.html`).
- Alternative hosts: Netlify Drop (drag the folder onto app.netlify.com/drop) or Cloudflare Pages. Publish-to-GitHub only works with the GitHub route.
- Audio: upload an mp3 to the repo (e.g. `audio/dasanadeno.mp3`) and paste `audio/dasanadeno.mp3` in the Audio field.
- Previewing locally: opening the files by double-click won't load `data.json`; use hosting, or run `python3 -m http.server` in the folder.
