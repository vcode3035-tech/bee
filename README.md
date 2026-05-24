Roblox Games – Static listing of popular Roblox titles

This repository hosts a simple **static HTML/JavaScript page** that
presents a curated collection of Roblox games. The site is fully
client‑side and does not require any server or backend components. All
data is embedded in the page itself.

### Features

- Three language options (English, Russian, Armenian) with a
  custom dropdown in the header.
- Category tabs (Tycoon, Simulator, Other, Donate) that filter the
  game list.
- Search box to quickly find games by name.
- Lightweight, no dependencies; can be deployed to any static host.

### Running locally

Simply open `ROBLOX.html` in a browser (no build step required). The
`css/` folder contains styles, and the game list is defined in the
script block of `ROBLOX.html`.

### Deployment

Since the page is static, you can host it on GitHub Pages, Netlify,
Vercel, or any other static‑file host. Just upload the repository contents
and point your domain where you like.

### Notes

- Legacy server files such as `server.js`, `app.js`, and
  `users.json` are no longer used but remain in the workspace for
  reference.
- Translation strings are stored directly within `ROBLOX.html` under the
  `translations` object.

Enjoy browsing the games!