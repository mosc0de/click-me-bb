# Date Invitation Website

A single-page interactive invitation hosted with GitHub Pages.

## Publish
1. Create a **public** GitHub repository named `date-invitation`.
2. Upload `index.html` and `.nojekyll` to the repository root (README optional).
3. Open **Settings → Pages**.
4. Set **Source: Deploy from a branch**, **Branch: main**, **Folder: /(root)**, then Save.
5. Visit `https://YOUR-USERNAME.github.io/date-invitation/` once deployment completes.

## Update
Open `index.html` on GitHub, click the pencil (Edit), make your changes, and **Commit changes** to `main`. GitHub Pages will republish automatically.

## Useful places to edit
- Date/time: search for `fixed-datetime` and the initial `summary-time` value.
- Brunch, shopping and dinner locations: search for `(undecided)` (also used in the sharing message).
- Telegram recipient: search for `TELEGRAM_USERNAME`.
- Heading and invitation: search for `Will you go on a date with me?`.

## Notes
- This is a static website: no database, login, or automatic RSVP collection.
- The Telegram button opens Telegram; it does not itself guarantee a message is sent.
- This public GitHub repository and its HTML contents can be viewed by others. Do not put passwords or private secrets in it.
- External CDN libraries and fonts require internet access.
