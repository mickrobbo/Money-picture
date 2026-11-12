# Money Picture

A phone-first personal finance app: net worth, super, investment property, debts, bills, crypto and where each pay went.

- Everything is saved on the device (browser local storage). No logins, no bank connections, nothing sent anywhere.
- Installable from Chrome (Install app / Add to home screen) and works offline.
- Back up from More → Make backup, restore with Load backup file.

Static site, no build step. Netlify publishes this folder as is (see `netlify.toml`).
To ship an update, change `index.html` and bump `VERSION` in `sw.js`.
