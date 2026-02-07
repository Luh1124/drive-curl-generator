# Cloud Download Tool

[中文](README.md)

A lightweight front-end tool that generates download commands for Google Drive and OneDrive, with dark mode and CN/EN language switch.

## Features
- Google Drive: paste share links and auto-extract file IDs
- OneDrive: paste full cURL and generate a ready-to-run command
- Follows system theme with manual toggle
- CN/EN language switch

## Live Demo
- GitHub Pages: `https://luh1124.github.io/drive-curl-generator/`

## Local Usage
1. Open `app.html` directly
2. Or host it with any static server (e.g. `python -m http.server`)

## Deploy to GitHub Pages
1. Create a new repo and push the code
2. Repo Settings → Pages → choose a branch (e.g. `main`) and root
3. Wait for deployment and open the generated URL

## How to Use
### Google Drive (share link supported)
1. Copy the share link or file ID
2. Paste into the input
3. Enter a filename
4. Generate the command and copy

### OneDrive (text guide)
1. Open the share link
2. Press `F12` and switch to `Network`
3. Click the page's Download button
4. Find the request named `download.aspx`
5. Right-click it → `Copy` → `Copy as cURL`
6. Paste the full cURL, generate and copy

### OneDrive (visual guide placeholder)
> You can add screenshots or a short video following this order:
1. Open the share page
2. `F12` → `Network` panel
3. Click download and locate `download.aspx`
4. Copy as cURL

## License
MIT
