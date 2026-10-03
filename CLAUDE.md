# FUMNSK PA website

## How the site works

- The whole site is a single file, `index.html`. GitHub Pages publishes it from the `main` branch (root folder).
- Live address: https://dleist1278.github.io/fumnsk-pa/

## Rules for every change

1. **Push to main after each change.** Commit straight to `main` and push. No branches or pull requests for this site.
2. **English and Spanish are always updated together.** The Spanish text lives in the `pa-es` JSON block in `index.html`. Each entry maps the exact English text (including any HTML tags inside it, such as `<b>`) to its Spanish version. The page matches on the exact English string, so whenever English text changes:
   - change the matching key in `pa-es` to the new English text, character for character, and
   - update the Spanish value to match the new meaning.
   Remove entries whose English text no longer appears on the page. After editing, confirm `pa-es` is still valid JSON.
3. **Do not hardcode sheet data.** Events, team Leads, meeting dates, and fundraising totals come from the published PA Master Sheet tabs (Web Events, Web Teams, Web Meetings, Web Fundraising), whose CSV links go in the `pa-sheet` JSON block. Changes to those belong in the Master Sheet, not in `index.html`. If asked to change one of them, say so instead of editing the file. (The built-in data in `index.html` is only a fallback for when the sheet can't be reached.)
4. **No em dashes, en dashes, or emojis in site text.** Use periods, commas, colons, or parentheses instead.

## Checking a change

- Verify both JSON blocks (`pa-es` and `pa-sheet`) still parse.
- After pushing, confirm the GitHub Pages build for the new commit finished successfully.
