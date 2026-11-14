# Publishing Cirrus on GitHub

1. Create a **public** repo named `cirrus-browser` (leave README, .gitignore and license unticked).
2. Upload everything in this folder **except** the hidden `.github` folder: `main.js`, `preload.js`, `package.json`, `README.md`, `LICENSE`, `CHANGELOG.md`, `GUIDE.md`, `.gitignore`, and the folders `src`, `build`, `docs`.
3. **Last**, create `.github/workflows/build.yml` on GitHub (**Add file → Create new file**) and paste in the contents of `docs/build.yml.txt`. Committing it starts the build.
4. Wait 15 to 25 minutes. The installers appear on the repo's **Releases** page automatically.
5. Repo **About** → add the description and topics from the README.
