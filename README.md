
# 2026CSAE100 — Class Games

Browser games used in **Computational Thinking with Programming (2026CSAE100)** at Bennett University.

Each game takes one idea from one lecture and makes it playable in about two minutes. Students scan a QR code on the slide, play, and then see the Python behind it.

## Live site

- **All games:** https://2026csae100.github.io/
- **Python or Not?** (Session 2) — https://2026csae100.github.io/python-or-not.html

## What is in this repository

| File | What it is |
|---|---|
| `index.html` | The hub page. Lists every game in the course. |
| `python-or-not.html` | Session 2 game — eight products, guess which ones have Python inside. |

Games for Sessions 5 and 6 (Mad Libs, The Mind Reader) are linked from the hub page but hosted elsewhere for now.

## How the games are built

Every game is a **single HTML file**. All the CSS and JavaScript sits inside that one file — there is nothing to install, no build step, no libraries to download, and no server-side code.

That means:

- You can open any file directly in a browser to test it, before uploading.
- Nothing can break because an external service went down.
- The games work on a phone, on classroom Wi-Fi, and offline once loaded.

## Adding a new game

1. Put the new `.html` file in the root of this repository (**Add file → Upload files**).
2. Open `index.html` and copy one of the existing `<a class="card">` blocks.
3. Change the session line, the game name and the description, and point `href` at your new file.
4. Commit. The site updates in a few minutes.

## Updating a game

Open the file on GitHub, click the pencil icon, edit, and commit. GitHub Pages redeploys automatically.

If a change does not show up, it is almost always the browser cache — reload with Ctrl+Shift+R (Cmd+Shift+R on a Mac).

## Course

Computational Thinking with Programming — 2026CSAE100
School of Computer Science Engineering and Technology, Bennett University
Academic session 2026–27
