# Gloria's Platter

A warm, premium catering website for Gloria's Platter. The site presents all
menus, items, and prices publicly, while orders are confirmed over WhatsApp
and paid through Venmo.

See [IMPLEMENTATION_PLAN.md](IMPLEMENTATION_PLAN.md) for the full project
roadmap, including content, ordering tools, quality checks, and launch tasks.

## Preview locally

This is a static site, so it does not need a build step:

```bash
python3 -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) and refresh after edits.
Stop the server with <kbd>Ctrl</kbd> + <kbd>C</kbd>.

## Publish with GitHub Pages

1. Push the `main` branch to GitHub.
2. Open **Settings → Pages** in the repository.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/(root)` folder, then save.

GitHub Pages publishes the site after the first build completes.
