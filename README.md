# Java for QA — Field Notes

A styled single-page site covering Java fundamentals for QA/automation engineers (JDK/JRE/JVM, variables, operators, I/O, if-else, switch, loops, arrays, strings, OOPs, Collections), built to run before moving into Selenium.

## ✨ Features

- Sticky "build progress" bar (compile-themed reading progress + current phase)
- Dark / light mode toggle (remembers your choice)
- Sidebar search to jump straight to a topic
- "Continue where you left off" banner
- Auto-calculated read time per section
- Copy & "Run in browser" buttons on every code block (opens an online Java compiler)
- End-of-phase quizzes (5 questions each, instant feedback + score) for Phase 1, 2, and 3
- Proper favicons + a social preview image (WhatsApp/LinkedIn/Twitter link cards)

## 📁 What's in this folder

```
index.html      ← the site itself
assets/         ← favicons + social preview image (og-image.png)
sitemap.xml     ← for search engines
robots.txt      ← for search engines
```

All four must be uploaded together and kept in this same relative structure (the `assets/` folder must sit next to `index.html`).

## Go live with GitHub Pages (free)

1. Create a new GitHub repository (e.g. `java-for-qa`).
2. Upload **all four items** (`index.html`, the `assets/` folder, `sitemap.xml`, `robots.txt`) to the **root** of that repo (drag-and-drop on github.com works, or `git push`).
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.
5. Wait ~1 minute. Your live URL will appear at the top of that same Settings → Pages screen:
   `https://<your-username>.github.io/<repo-name>/`

That's it — no build step, no server needed, it's a static HTML file.

## ⚠️ One thing to update after deploying

Open `index.html` and search for `your-username` (appears in the `<meta property="og:...">` tags near the top). Replace it — and the repo name if different from `java-for-qa` — with your real GitHub Pages URL, e.g.:

```
https://monika-dev.github.io/java-for-qa/
```

Do the same inside `sitemap.xml` and `robots.txt`. This is what makes link previews (WhatsApp/LinkedIn) and search engines point to the right place.

## Updating content later

Just edit `index.html` directly on GitHub (pencil icon on the file) or push changes via git — GitHub Pages redeploys automatically within a minute or so.
