# Campaign Wiki

A simple static wiki for a Dungeons &amp; Dragons campaign, ready to publish with **GitHub Pages**. No build tools, no frameworks — just HTML and CSS you can edit in any text editor.

## Pages

- `index.html` — Home, with a quick overview and current quest
- `characters.html` — Player characters and NPCs
- `locations.html` — Cities, dungeons, and regions
- `sessions.html` — Chronological session log
- `lore.html` — Religion, major historical events, and ancestries
- `ancestries.html` — Detailed reference for the peoples of the world
- `css/style.css` — Shared parchment-themed styling

## Preview locally

Just double-click `index.html` to open it in your browser. Everything is relative-linked, so it works straight from disk.

## Publish with GitHub Pages

1. Commit and push the repository to GitHub.
2. On GitHub, go to **Settings → Pages**.
3. Under **Source**, select **Deploy from a branch**.
4. Choose the `main` branch and the `/ (root)` folder, then **Save**.
5. After a minute, your wiki will be live at:

   ```
   https://<your-username>.github.io/<repo-name>/
   ```

The `.nojekyll` file is included so GitHub serves the files as plain static HTML (no Jekyll processing).

## Customizing

- Change the campaign name in the `<h1 class="site-title">` block of each page.
- To add a new page, copy one of the existing HTML files, update the `<title>`, the nav `class="active"` link, and the content inside `<main>`.
- Colors and fonts live at the top of `css/style.css` as CSS variables (`--parchment`, `--accent`, etc.).
- Add images to an `images/` folder and reference them with `<img src="images/your-file.png" alt="...">`.

May the dice favor the bold.
