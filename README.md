# Behind the Demo website

Static submission website for the CHI 2027 Meet-Up **Behind the Demo: The People Who Build Physical HCI**.

## Quick preview

### Easiest option
Open `index.html` directly in a web browser.

### Recommended local preview
Run a small local web server from this folder.

**Windows (PowerShell or Command Prompt)**

```bash
cd path\to\behind-the-demo-site
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

If `python` is not recognized, try:

```bash
py -m http.server 8000
```

**macOS / Linux**

```bash
cd path/to/behind-the-demo-site
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

Stop the server with `Ctrl+C`.

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `behind-the-demo`.
2. Upload **the contents of this folder** to the repository root. Do not upload only the ZIP file.
3. Commit and push the files.
4. On GitHub, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/ (root)` folder, then save.
7. GitHub will show the public site URL after deployment finishes.

This site uses only static HTML/CSS/assets, so no special Jekyll theme or plugin is required. `_config.yml` is included so the repository is also compatible with GitHub Pages' default Jekyll processing.

## Main files

- `index.html` — page content
- `assets/css/style.css` — visual design
- `assets/img/behind-the-demo-logo.png` — meet-up logo
- `assets/img/meetup-flow.png` — activity-flow figure
- `assets/img/organizers/` — organizer photos
- `_config.yml` — minimal GitHub Pages/Jekyll configuration

## Editing

Most text can be changed directly in `index.html`. Visual styles can be adjusted in `assets/css/style.css`.
