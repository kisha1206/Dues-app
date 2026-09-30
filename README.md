# Dues website

The website for **Dues: Bill Tracker & Reminder**, on Android and iOS. It's a static site served by GitHub Pages at <https://kisha1206.github.io/Dues-app/>.

| Page | Path | Used for |
| --- | --- | --- |
| Landing page | `/` | Marketing, links to both stores |
| Privacy Policy | `/privacy/` | Play Console and App Store Connect privacy policy URL |
| Terms of Service | `/terms/` | Terms / EULA link in the apps and store listings |
| Support | `/support/` | App Store Connect support URL, FAQs |
| Delete account | `/delete-account/` | Play Console account-deletion URL |

Plain HTML and CSS: no build step. Shared styles are in `assets/styles.css`. To preview locally, run:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

Pushing to `main` redeploys the site.
