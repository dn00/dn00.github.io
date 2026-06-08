# dn00.github.io

Personal site for Dennis Nguyen — [dn00.github.io](https://dn00.github.io).

A single self-contained `index.html`: an interactive terminal where commands
(`whoami`, `ls projects/`, `cat giant.md`, `open resume.pdf`, `contact`) reveal
each section. Press **Enter** to walk through them one at a time, type a command,
or tap a chip.

No build step, no framework. Vanilla HTML/CSS/JS, served as-is on GitHub Pages
(`.nojekyll`). Assets (résumé PDF, favicon, images) live under `assets/`.

Run locally: open `index.html`, or `python3 -m http.server` then visit
`localhost:8000`.
