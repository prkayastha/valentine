# Valentine Website 💖

A simple, minimal Valentine page you can host with **GitHub Pages**.

## Features

- Romantic minimal UI with a Valentine question.
- `No` button moves away with motion when hovered/touched.
- Background YouTube music from your selected song, starting at **0:10**.
- Works even in local file mode with a **Play Music** click and an **Open on YouTube** fallback button.

## Run locally

### Option A (double click file)
Open `index.html` directly in your browser.

### Option B (recommended local server)
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.

## Host on GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or your default branch), folder `/ (root)`
4. Save and wait ~1 minute.
5. Your site will be live at:
   `https://<your-username>.github.io/<repo-name>/`
