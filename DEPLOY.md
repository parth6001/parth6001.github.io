# Parth Labs website — deployment instructions

Files:
- index.html: complete single-file responsive website. Replace the **root** `index.html` in the `parth6001/parth6001.github.io` repository with it.
- CNAME: optional custom-domain setting. Keep it **only if you actually own the domain and DNS points to GitHub Pages**.

## Update the existing GitHub Pages website
1. Open https://github.com/parth6001/parth6001.github.io
2. On main branch open index.html > Edit (pencil) OR use Add file > Upload files; replace existing root index.html.
3. Commit changes to main. Do not rename the file and do not upload it to a new folder.
4. In Settings > Pages confirm build source: Deploy from a branch, branch main, /(root), then check Actions or the deployment status.
5. If a CNAME file is present, GitHub Pages may redirect parth6001.github.io to that custom domain. Verify the domain is registered and DNS records are correct. If you do not own/operate the custom domain yet, remove CNAME and clear the custom domain in Settings > Pages to restore parth6001.github.io.
6. Wait for deployment then hard-refresh. On Android Chrome open a new incognito tab or remove just the site's cached files if needed. Avoid clearing storage for unrelated apps.

## Notes
- Five verified public repositories are included as static cards (Test Army QA, MindOrbit, Auralis, Wallpaper Studio, empty MyReminder).
- The browser attempts to fetch the GitHub public repositories API so additional future public repos can appear automatically; if blocked, the existing five cards remain usable.
- GitHub avatar image requires an Internet connection. No other paid services, frameworks, build steps or API keys are required.
- The project mockups are decorative representations, not screenshots of actual app runtime.
- Contact email is public as requested: parth6004@gmail.com.
