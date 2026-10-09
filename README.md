# Library Passport

A family passport for collecting library visits around Greater Boston, plus Monson and Seattle. Each person gets their own passport, earns a stamp at every library they visit, and unlocks badges along the way.

It's a single HTML file with no build step, designed to be added to an iPhone Home Screen.

## Features

- **Passport:** a cover with progress, and one page per library system with an ink stamp for each visit. Each system has its own stamp color and shape.
- **Profiles:** kid passports get a "library quest" at each library. Adult passports log hours worked and focus.
- **Explore:** search all 20 libraries and filter by Open Sunday, Open late, Quiet rooms, Lots of outlets, Favorites, Red/Blue/Green Line, or Not stamped yet.
- **Library details:** hours, transit, notes on working there, outlets, and links for directions and the library's website.
- **Badges:** First Stamp, Explorer, Navigator, Full Passport, System Complete, Out of Town, Sunday Explorer, Night Owl, Regular, and Quest Master or Deep Worker.
- Light and dark themes.

## Data

- **Library list:** a snapshot of the "Libraries to Visit" Notion database (October 2026), embedded in `library-passport.html` as the `LIBS` array.
- **Stamps and profiles:** where they're saved depends on how you open the page.
  - **As a claude.ai Artifact:** they're stored in the artifact's shared database and sync across devices.
  - **Opened anywhere else (local file, GitHub Pages):** they're saved in that browser's `localStorage`, on that device only.

## Running it

Open `library-passport.html` in a browser. On iPhone, open it in Safari, then tap Share → Add to Home Screen.
