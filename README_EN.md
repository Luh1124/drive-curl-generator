# Cloud Download Tool

[中文](README.md)

A lightweight front-end tool that generates download commands for Google Drive and OneDrive, with dark mode and CN/EN language switch.

## Features
- Google Drive: paste share links and auto-extract file IDs
- OneDrive: paste full cURL and generate a ready-to-run command
- Follows system theme with manual toggle
- CN/EN language switch

## Live Demo
- GitHub Pages: `https://<your-username>.github.io/<repo-name>/`
- Custom domain: `https://your-domain.com/`

## Local Usage
1. Open `app.html` directly
2. Or host it with any static server (e.g. `python -m http.server`)

## Deploy to GitHub Pages
1. Create a new repo and push the code
2. Repo Settings → Pages → choose a branch (e.g. `main`) and root
3. Wait for deployment and open the generated URL

## How to Use
### Google Drive
1. Paste a share link or file ID
2. Enter a filename
3. Generate the command and copy

### OneDrive
1. Open the share link → F12 → Network
2. Click download, find `download.aspx`
3. Right-click the request → Copy as cURL
4. Paste cURL, generate and copy

## Config
- Update GitHub link:
  - In `app.html`, search for `https://github.com/yourname/drive-download` and replace it with your repo URL

## License
MIT
