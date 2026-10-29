# Signal — UX evidence to action

A no-build, static HTML dashboard for sharing anonymized UX evidence, product behavior signals, and suggested next steps. It uses sample content only and can be hosted on GitHub Pages.

## Update the content

Open `index.html`. The `insights` list near the bottom of the file contains the example signals. Copy an entry and update its title, detail, source (`Research`, `Behavior`, or `Support`), priority (`High`, `Medium`, or `Low`), area, and date. Summary numbers and the suggested actions are separate HTML text, so update those when your team metrics change.

Keep evidence aggregated and anonymized. Do not commit customer names, identifiable quotes, or confidential product data to a public repository.

## Publish with GitHub Pages

1. Create a GitHub repository and add `index.html` and `README.md` to its root.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select your default branch and the `/ (root)` folder, then save.
4. GitHub will show the published site URL in the Pages settings.

There is no build step or external dependency. The site works on mobile and desktop.
