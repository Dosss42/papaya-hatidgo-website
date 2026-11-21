# Papaya HatidGo: website

The public homepage of **Papaya HatidGo**, tricycle rides in General Tinio (Papaya), Nueva Ecija (a BSIT project).
It explains the app to passengers, drivers, the TODA and the LGU, and links to the download and the
[user manual](https://dosss42.github.io/papaya-hatidgo-manual/).

- One page: `index.html` (no build step), the screenshots and logo in `img/`.
- Light and dark follow the phone; the sun/moon button in the header switches them.
- **Ask HatidGo (beta):** the "Ask a question" button opens a small helper that answers common questions
  (fares, booking, discounts, drivers, download). It runs only in the browser: it matches the question's words
  (English or Taglish) against a fixed list of answers in `index.html` (`ANSWERS`). No server, no AI, nothing
  stored. To teach it a new answer, add an entry with its `words`, `say` and optional `link` / `next`.
- To publish on GitHub Pages: push this folder to a new repo, then Settings › Pages › Deploy from branch `main` / root.

The "Download for Android" buttons use the newest APK on the manual repo's Releases.
