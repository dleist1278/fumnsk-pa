# FUMNSK Parent Association website

The PA's public website. It is one page with two views: the home page and the Get involved page (the same address with `#join` at the end).

## What's in this folder

| File | What it is |
|---|---|
| `index.html` | The whole website: text, design, photos, and Spanish translation |
| `og-image.jpg` | The picture that shows when someone shares the link in a text or email |
| `apple-touch-icon.png` | The icon used when someone saves the site to their phone's home screen |
| `CNAME` | The custom web address (only present once a domain is set up) |

## Day-to-day updates: use the Master Sheet, not this folder

Most changes never touch this folder. Edit the PA Master Sheet in Google Drive and the website updates within about 5 minutes:

- **Web Fundraising:** totals by source, an optional goal, and an "Updated" date
- **Web Events:** dates, descriptions, an optional Spanish description, and an optional SignUpGenius link
- **Web Teams:** Lead names (leave blank to show "Needs a Lead")
- **Web Meetings:** PA meeting dates

Only those four tabs are published. Never publish the whole spreadsheet, since other tabs contain family contact details.

If the sheet can't be reached, the site shows the built-in information in `index.html` instead, so it never appears broken.

## Changes that do need a new index.html

Team descriptions, FAQ answers, links (forms, Venmo, store), and photos live inside `index.html`. To change them:

1. Get an updated `index.html`.
2. In this repository on GitHub, choose **Add file > Upload files**, upload it, and select **Commit changes**.
3. The live site updates within a few minutes.

## Publishing settings

GitHub Pages is set to **Settings > Pages > Deploy from a branch > main > / (root)**. If a custom domain is used, it is entered under **Settings > Pages > Custom domain**, with **Enforce HTTPS** turned on.

## Who to ask

PA email: fumnsparents@gmail.com
