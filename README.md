# Cookie Consent Alignment Study — landing page

This repository hosts the public download page for the **Cookie Consent
Alignment Study** browser extension (GWUSEC, IRB-approved research study).

The site is built as a static page suitable for [GitHub Pages].

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The landing page. |
| `styles.css` | Page styles (AMO-inspired, neutral branding). |
| `firefox-extension.zip` | The downloadable extension package linked from the page. |

The original `Cookie Consent Alignment Study – Get this Extension for 🦊
Firefox (en-US).htm` and its `_files/` directory are kept only as a visual
reference and are **not** served by the published site.

## Publishing on GitHub Pages

Following <https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site>:

1. Push this folder to a GitHub repository (e.g. `cookie-consent-alignment-study`).
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Select the branch (typically `main`) and the `/ (root)` folder, then
   **Save**.
5. After a minute or two GitHub will show the published URL, e.g.
   `https://<your-user>.github.io/<repo>/`. The download link on the page
   resolves to `firefox-extension.zip` in the same folder.

## Updating the extension

To ship a new build, replace `firefox-extension.zip` with the new file
(keeping the same filename) and update the version / size / "Last updated"
fields in `index.html`. Commit and push — GitHub Pages will redeploy
automatically.

## Notes

* No Firefox or Mozilla logos or trademarks are used on this page; it is an
  independent landing page for an IRB-approved research extension and is not
  affiliated with addons.mozilla.org.
* The page links to the Mozilla Public License 2.0 text on
  <https://www.mozilla.org> only as a license reference.

[GitHub Pages]: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
