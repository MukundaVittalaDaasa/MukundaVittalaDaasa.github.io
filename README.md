# Mukunda Vittala · ಮುಕುಂದ ವಿಠ್ಠಲ

**Website:** https://mukundavittaladaasa.github.io
**Admin (edit and publish):** https://mukundavittaladaasa.github.io/admin.html

## Updating the site
1. Open the Admin link above. First time only: Connect tab → paste your GitHub token.
2. Pieces: your kritis, ugabhoga and blogs. Site: click any text in the preview to edit its words and look. Files: audio, images, backup.
3. Press **Publish**. The site updates in about a minute.

## How it is organised
- One small file per piece in `data/<section>/`, one list in `data/index.json`, settings in `data/site.json`. Adding pieces never slows the site, so hundreds or thousands are fine.
- New section (for example "Stotra")? Pages → Add a section. No code change.
- Backup: Files → Download backup, now and then.

## Files
- `index.html`, `admin.html`: the site and the editor. Replace only when given new ones (delete the old first).
- `data/`: all content, written by Publish. Never edit by hand.
- `audio/`: small audio files. Files over 25 MB go to Releases automatically (Connect → Where audio is stored).

Licence: CC BY-NC-ND 4.0 (see LICENSE.md).
