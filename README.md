# Mukunda Vittala · ಮುಕುಂದ ವಿಠ್ಠಲ

ಶ್ರೀಕೃಷ್ಣಾರ್ಪಣಮಸ್ತು

Kritis and devotional compositions in praise of Hari, written in Kannada with the ankita **Mukunda Vittala**.

**Read them on the website: https://mukundavittaladaasa.github.io**

## About

Small offerings at the feet of Hari, written with little learning and much hope. This repository holds the website above and is the permanent archive of the works.

## What is here

```
index.html            the public website
admin.html            the editor (add, change, publish)
LICENSE.md            terms of use
data/
  site.json           title, About page, look, footer, labels
  index.json          a light list of every piece (title, type, date, tags, first line)
  kriti/              one small file per kriti
  ugabhoga/           one small file per ugabhoga
  blog/               one small file per blog
images/  kritis/      photos and PDFs
```

The website loads only the light list first and opens a piece's own file when it is tapped, so it stays fast with thousands of pieces. Each Publish is one commit that updates only what changed.

## License

© 2026 Mukunda Vittala · ಮುಕುಂದ ವಿಠ್ಠಲ. Licensed under [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/): the works may be shared with credit to Mukunda Vittala, unchanged and not for sale. For any other use, please ask the author. See `LICENSE.md`.

---

<details>
<summary>Owner's guide: how to update the site</summary>

### The editor (admin.html), five areas
- **Pieces**: search, add, edit and delete. Each pallavi, charana or verse has a **Translation** tab (English, ಕನ್ನಡ, हिन्दी) and an **Audio** tab (upload mp3, wav, m4a, ogg, flac…).
- **Pages**: the words of every page: first page, About, each section (its button name, Kannada line and introduction), footer and license, browser title, and every word on the site. Changes apply as you type.
- **Design**: a live preview of the real website. Tap any text in it to open that text's size and font controls. Colours, letter style and the style of translations are here too.
- **Files**: upload audio, photos and PDFs, and see everything already uploaded.
- **Connect**: the one-time GitHub connection.
Press **Publish** (top right) when you are happy. The first time after an update it also moves any older works into the `data/` folders.

### Files tab
Upload photos (go to `images/`) or PDFs (go to `kritis/`) and copy the path it shows.

### One-time connection (token)
1. Open `github.com/settings/tokens/new` (choose **Tokens (classic)**), name it `kriti-editor`, set the longest expiry, tick only **`public_repo`**, and generate it.
2. In the editor, open **GitHub connection**, paste the token, tap **Save connection**, then **Test connection**.
3. When the token expires, make a new one the same way. Never share it with anyone.

### Good to know
- File names must stay exactly `index.html`, `admin.html`, `data.json`, `LICENSE.md`, `README.md`. If a phone adds `-1` or `-2` to an upload, delete the old file on GitHub and rename the new one.
- Full text can also live in a PDF: upload it to a `kritis/` folder (the editor does this for you) and link it from the work.
- Copyright, license and footer text are editable in the editor under **Site details**.
- Backup: use **Code → Download ZIP** on GitHub now and then, and keep a copy in your own cloud storage.
- Own address later: buy `mukundavittala.com` (or `.in`) with auto-renew on, then add it under **Settings → Pages → Custom domain**.

</details>

## Styling every piece of text (Design tab)

Under **Style each piece of text**, open a page (Home page, Top of every page, About, each of your sections, Footer). Every part has its own font (English and ಕನ್ನಡ), size (50–250%), weight, slant and capitals (UPPERCASE / Capitalize / lowercase / As written). Tap any text in the live preview to jump to its controls. "Default" keeps the original look. The older "Broad sizes" group controls still work and combine with these.

## Audio storage

- Up to 25 MB: stored with the website (audio/ folder). Up to 60 MB if you choose "Always with the site".
- Larger files: stored in your repository's **Releases** (tag `audio`, up to 2 GB per file) and played from there. They do not count towards the website's size.
- Choose the behaviour in **Connect → Where audio is stored**. The Files tab lists both kinds and copies their links.
- Tip: a mp3 at 96 kbps is about 0.7 MB per minute, so most kritis stay under 10 MB.
- If the upload to Releases is blocked by your browser, open the repository → Releases → audio → Edit, attach the file, and paste its link into the audio box.
