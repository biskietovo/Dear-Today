# Dear Today - Three emoji diary
this website is a scrapbook style daily diary built with HTML, CSS and JavaScript. In this website, you can capture a day with any three emojis, an optional title and an optional note. It also includes a live preview, browser-local saving, a flip-through notebook, a monthly calendar, edit/delete and validation.
## How to run it
1. open the website:https://biskietovo.github.io/Dear-Today/
2. Open "index.html" in a modern browser.
3. Stop the server with "Ctrl+C".

## How to use it
you can choose a date and any type of emojis into each three boxes to decorate your own diary book.

you can add an optional title or note, it's up to you.
- Live preview updates automatically when you change your content.
- Browse emoji categories, search keywords or pick from frequently used emojis in the emoji pocket.
- Click save to store your diary page inside your browser. Saving same date will overwrite old entry.
- Go to **My notebook** to flip through saved pages, edit or delete existing entries.
- Go to **Calendar** to view marked saved dates, create or open diary for selected day.
- Use export button to download current diary draft as PNG image.

## Storage and limitations
All entries are saved in your browser via `localStorage`. No account or backend server needed.
- Diary will be lost if you clear browser data, change browser or open file from different location.
- Only one entry allowed per date. Re‑saving a date updates existing page instead of creating duplicate.
- Twemoji emoji artwork requires internet; offline will show text emoji fallback.

## Project files
- `index.html` — website HTML structure
- `style.css` — scrapbook styling and responsive layout
- `script.js` — interactions, storage, calendar, notebook and PNG export logic
- `PROCESS.md` — development process and user testing template
- `CREDITS.md` — credits for fonts, emoji assets and development help
