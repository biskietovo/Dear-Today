# Dear Today - Three emoji diary
this website is a scrapbook style daily diary built with HTML, CSS and JavaScript. In this website, you can capture a day with any three emojis, an optional title and an optional note. It also includes a live preview, browser-local saving, a flip-through notebook, a monthly calendar, edit/delete and validation.

## How to run it
https://biskietovo.github.io/Dear-Today/

## Features
- Three-emoji diary entries. Choose three emojis to represent the day. The same emoji can be used more than once.
- Emoji pocket — browse emoji categories, search the built-in collection, or choose from a small frequently used section.
- Optional title and note, keep an entry minimal or add a little more context.
- Live preview — see the diary page as you write.
- Notebook view — revisit saved entries and move between pages.
- Calendar view — see which dates have saved entries.
- Edit and delete — update an existing diary page or remove it.
- Scrapbook-inspired visual design — soft colours, notebook-like panels, and handwritten-style details.

## Project files
- `index.html` — website HTML structure
- `style.css` — scrapbook styling and responsive layout
- `script.js` — interactions, storage, calendar, notebook and PNG export logic
- `PROCESS.md` — development process and user testing template

## Saving and Privacy
Diary entries are stored in the browser's localStorage on the device and browser being used. There is no account system or server-side diary storage in this version.

Because entries are stored locally, they do not automatically sync between different browsers or devices. Clearing the browser's site data may remove saved entries, so users should keep this limitation in mind.

## Emoji artwork
The emoji picker and diary displays use Twemoji artwork where supported, helping keep emoji visuals more consistent across the picker, selected slots, preview, notebook, and calendar. The browser needs an internet connection to load the Twemoji SVG assets from the configured CDN.

## Credits and Acknowledgements
- Twemoji — emoji artwork by Twitter, Inc. and contributors. Twemoji graphics are licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0). Project repository: jdecked/twemoji.
- Google Fonts — the interface uses DM Mono, DM Sans, and Patrick Hand from Google Fonts.
- Development Support — ChatGPT was used as a support tool during planning, coding, debugging, and documentation. The project direction, design decisions, testing, and final acceptance of changes were guided by me.

Thank you to everyone who takes the time to try Dear Today and share feedback.


