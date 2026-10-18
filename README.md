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

### Everyday routine
1. Open `https://mukundavittaladaasa.github.io/admin.html` on any device.
2. **Works → + New piece** (use the search box and type filter to find older pieces). Choose the type:
   - **Kriti**: pallavi, anupallavi (optional, leave empty to skip), charanas.
   - **Ugabhoga**: verses only, no pallavi or anupallavi.
   - **Tattva writing**: a blog-style article (headings, bold, quotes, links, pictures).
3. Under every pallavi, charana or verse, open **Meaning / summary** and type it in English, ಕನ್ನಡ and/or हिन्दी. Readers tap ⓘ (or the lines) and choose their language.
4. **Save piece**, then **Publish**. The site updates in about a minute.

### First time after this update
Open the editor once and press **Publish**. It moves your existing works from `data.json` into the `data/` folders. Keep `data.json` as a backup.

### What visitors see
The website opens on a quiet first page with four buttons: **About**, **Kritis**, **Ugabhoga** and **Tattva Chintane**. A list appears only when a button is tapped. Tap the name at the top of any page to return.

### Site tab
Title, description, About page, colours, text size, letter style, footer, license, the list of types ("Name | layout | Button name | Kannada subtitle" per line; layouts are kriti, verses, article; each type becomes a button on the website) and every word on the site can be changed here. Press **Save site settings**, then **Publish**.

The **Look** section lets you choose the fonts of the first page (English and Kannada, with a preview). It also controls how meanings and summaries appear: italics, size, colour and frame, with a live preview.

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
