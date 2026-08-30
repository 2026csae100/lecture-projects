# 2026CSAE100 — Class Games

Browser games used in **Computational Thinking with Programming (2026CSAE100)** at Bennett University.

Each game takes one idea from one lecture and makes it playable in about two minutes. Students scan a QR code on the slide, play, and then see the Python behind it.

## Live site

The site is published with GitHub Pages from this repository. Because the repository is a *project* site (not the account's main site), every address starts with the repository name:

- **Hub page (all games):** `https://2026csae100.github.io/lecture-projects/`
- **Python or Not?** — `https://2026csae100.github.io/lecture-projects/python-or-not.html`
- **The Bouncer** — `https://2026csae100.github.io/lecture-projects/bouncer.html`

If the repository has a different name, replace `lecture-projects` with that name. The exact address is shown under **Settings → Pages** in the repository.

`https://2026csae100.github.io/` on its own returns 404 unless a repository named exactly `2026csae100.github.io` exists. That is normal for a project site.

## What is in this repository

| File | What it is |
|---|---|
| `index.html` | The hub page. Lists every game in the course. |
| `python-or-not.html` | Python or Not? — eight products, guess which ones have Python inside. |
| `session3-build-the-program.html` | Build the Program — put the pieces of a Python line in order. |
| `madlibs.html` | Mad Libs — four words in, one story out; the whole game is input() and an f-string. |
| `mindreader.html` | The Mind Reader — think of a number; one expression always knows the answer. |
| `bouncer.html` | The Bouncer (Lecture 5) — gate duty, six visitors, one if statement. |

The hub page links to every file above by these exact names. If a file is missing or named differently (for example `python_or_not.html` with an underscore), its card on the hub page opens a 404. File names are case-sensitive on GitHub Pages.

## How the games are built

Every game is a **single HTML file**. All the CSS and JavaScript sits inside that one file — there is nothing to install, no build step, no libraries to download, and no server-side code.

That means:

- You can open any file directly in a browser to test it, before uploading.
- Nothing can break because an external service went down.
- The games work on a phone, on classroom Wi-Fi, and offline once loaded.

## Adding a new game

1. Put the new `.html` file in the root of this repository (**Add file → Upload files**).
2. Open `index.html` and copy one of the existing `<a class="card">` blocks.
3. Change the lecture line, the game name and the description, and point `href` at the new file name.
4. Commit. The site updates in a few minutes.
5. Make the QR code for the slide from the full address, for example `https://2026csae100.github.io/lecture-projects/bouncer.html`.

## Updating a game

Open the file on GitHub, click the pencil icon, edit, and commit. GitHub Pages redeploys automatically.

If a change does not show up, it is almost always the browser cache — reload with Ctrl+Shift+R (Cmd+Shift+R on a Mac).

## Checking that a link works

Open the address in a private/incognito browser window. If you see a GitHub 404 page:

- check the file name in the address matches the file name in the repository exactly, including hyphens, underscores and capital letters;
- check the address includes the repository name after `2026csae100.github.io/`;
- check **Settings → Pages** shows the site as published from the `main` branch, root folder.

## Course

Computational Thinking with Programming — 2026CSAE100
School of Computer Science Engineering and Technology, Bennett University
Academic session 2026–27
