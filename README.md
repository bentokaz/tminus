# T-Minus

Countdowns, timers and stopwatches, each shown full screen in one of 24 animated themes, or one you design yourself.

- **Countdowns** for anything with a date. They can repeat every week, month, year or every few days, and carry a note or a link.
- As many **timers** and **stopwatches** as you like, each with its own theme. Timers have presets from 1 minute to 2 hours or any custom time; stopwatches have laps. They keep correct time if the page is closed and reopened.
- **Custom themes**: your own colours, font, digit style, motion and background picture.
- **Installable**: add it to your home screen or desktop, and it works offline.
- Swipe a row left to delete it, with Undo.
- A calendar in the editor highlights popular holidays and events.
- **Share link** packs a countdown into the address, so anyone who opens the link sees it and can save it to their own list.
- A chime at zero, an optional browser notification while the page is open, and the screen stays awake in the full-screen view.
- Export and import a backup file. Add a countdown to your calendar as an `.ics` file. Slideshow through all countdowns.
- Everything is saved in your browser. Nothing is sent to a server.

Themes: Departure board, Minimal, Retro terminal, Night sky, Nature, Ocean, Arcade, Blueprint, Snowfall, Sunset drive, Aurora, Neon sign, Rainy window, Chalkboard, Party, Lava lamp, Vinyl, Dunes, Circuit, Clouds, Forest, Coral reef, Mountain lake, Cherry blossom.

The app is one file, `index.html`, plus a small offline worker (`sw.js`), a manifest and icons. No dependencies beyond Google Fonts.

## Hosting on GitHub Pages

In the repository: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, branch `main`, folder `/ (root)`. The site appears at `https://<username>.github.io/<repository>/` a minute or two later.
