# Production Tracker

Gold chain production batch tracker (melting to finishing) with login, roles, saved records, dashboard and Excel export.

## Publish on GitHub Pages
1. Sign in to GitHub and create a new repository (for example `production-tracker`).
2. Click **Add file > Upload files** and upload `index.html` and `.nojekyll` (keep `index.html` in the root).
3. Commit the files to the `main` branch.
4. Open **Settings > Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
5. After a minute your site is live at `https://YOUR-USERNAME.github.io/production-tracker/`.

## First login
- Username: `admin`
- Password: `admin123`
- Change it straight away in **Account**.

## Important
- GitHub Pages is static hosting. Users, passwords and saved sheets are stored in the **browser of each person** (localStorage), not on a server. Another browser or PC starts empty.
- Use **Download Excel** on the Records page regularly to keep a backup.
- The login is a convenience screen only. The code is public, including the default password, so do not rely on it to protect sensitive data.
- Excel download loads a small library from cdnjs, so it needs an internet connection.
