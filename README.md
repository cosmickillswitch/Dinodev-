# DEV: Dino Survival

A 3D dinosaur survival + building game in HTML/JavaScript (Three.js). You play **DEV**, an avatar puppeted by a team of game developers with god-mode powers.

## Play on GitHub Pages
1. Upload every file in this folder to the root of a GitHub repository.
2. Repo **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save**.
3. After a minute it's live at `https://<your-username>.github.io/<repo-name>/`.

## Add to home screen
- **iPhone/iPad (Safari):** Share → *Add to Home Screen*.
- **Android (Chrome):** ⋮ menu → *Install app* / *Add to Home screen*.

It opens fullscreen like an app. After the first load it also works offline (the service worker caches the game and Three.js).

## Controls
Desktop: WASD move · mouse look/attack · Space jump · Shift sprint · B build · R rotate · I craft · E eat · H heal · F fly (Space up / C down) · G god mode · T or Enter DEV console.
Touch: left stick to move, drag right side to look, on-screen buttons for everything else.

## DEV console
Type plain English, e.g. `summon a rocket launcher and 3 tame raptors`, `give me 300 iron`, `build a tech fort`, `giant t-rex`, `make it night`, `meteor shower`, `level 15`.
Commands are parsed locally in the browser (no server or API key needed).

Progress saves in your browser's local storage.
