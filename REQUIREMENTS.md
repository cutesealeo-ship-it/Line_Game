# Requirements

Strawberry Slide is a single static HTML file. There is nothing to install or build.

## To play
- A modern desktop or mobile browser: Chrome, Edge, Firefox or Safari (current versions).
- JavaScript enabled.
- `localStorage` enabled (used to save accounts and progress on the device).

## To host on GitHub Pages
1. Push `index.html` to a repository.
2. Go to **Settings → Pages**, choose your branch and the `/ (root)` folder, then save.
3. Open `https://<your-username>.github.io/<repo-name>/`.

You can also open `index.html` directly from disk or serve it with any static host.

## Dependencies
| Item | Needed? | Notes |
|------|---------|-------|
| npm, pip or any build tool | No | No package manager files are needed. |
| JavaScript libraries | No | All game code is inline in `index.html`. |
| Google Fonts (Fredoka) | Optional | Loaded from `fonts.googleapis.com`. If it is blocked or offline, the game falls back to system fonts. |
| Internet connection | Optional | Only needed for the font. The game runs offline. |

## Feature notes outside claude.ai
- **Local accounts and guest mode** work anywhere. Accounts, passwords (hashed with SHA-256 and a salt) and progress are stored in the browser on that device only. Clearing site data erases them.
- **"Continue as (your Claude name)" cloud sync** only works when the page is opened inside claude.ai. On GitHub Pages the button stays hidden and the game uses local accounts.
- Because accounts are local, the password check is a convenience for sharing a device, not real security.

## Controls
W A S D or arrow keys, on-screen buttons, or swipe. R restarts the level, Esc opens the levels menu.
