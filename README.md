# Planthology — marketing site

The GitHub Pages site for [Planthology](https://islerm.github.io/planthology-site/),
an iOS planner that unifies everyday scheduling and trip planning.

- `index.html`: landing page (features, screenshots, feedback, projects, about)
- `privacy.html`: privacy policy (App Store "privacy policy URL")
- `support.html`: support & FAQ (App Store "support URL")
- `snowball/`: Snowball Budget landing, privacy, and support pages
- `fibrofog/`: FibroFog landing, privacy, and support pages (Flutter app; iOS now, Android coming soon)
- `pitcrew/`: Pit Crew Coach portfolio page (open-source iRacing coach in Rust; feedback goes to its own repo)
- `.github/ISSUE_TEMPLATE/`: bug report & feature request templates; Issues on
  this repo are the app's public feedback channel

Plain HTML/CSS, no build step. Edit and push; GitHub Pages redeploys
automatically.

## Updating screenshots

Images live in `assets/img/`. They're simulator captures resized to ~1000 px
tall; replace them with fresh captures whenever the UI changes.

## App feedback

🐞 [Report a bug](https://github.com/islerm/planthology-site/issues/new?template=bug_report.md) ·
💡 [Request a feature](https://github.com/islerm/planthology-site/issues/new?template=feature_request.md)
