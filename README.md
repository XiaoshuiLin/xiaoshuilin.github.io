# Xiaoshui Lin — Academic Website

A complete English-language academic website, ready for GitHub Pages.

## Preview

Open `index.html` in a browser. The site has no package dependencies and requires no build step. Navigation, the portrait, and the bibliography work directly from the files.

## Publish on GitHub Pages

1. Sign in to GitHub and create a public repository named `YOUR-USERNAME.github.io`, replacing `YOUR-USERNAME` with your actual GitHub username. Enable **Add README** when creating it.
2. Extract the website ZIP on your computer. Upload the **contents** of this folder to the repository root with **Add file → Upload files**. Upload the HTML files and the complete `assets` folder; do not upload the ZIP itself or place everything in another enclosing folder. Commit the files to `main`.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, select **main** and **/(root)**, and click **Save**.
5. When deployment completes, click **Visit site**. The address will be `https://YOUR-USERNAME.github.io/`. Publishing can take up to 10 minutes.

If using the Git command line, include the `.nojekyll` file. Browser uploads may not display hidden files; this site also works without that file because it uses plain HTML/CSS and ordinary asset names.

For a project repository with another name, the website will instead be at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`. All local links are relative, so this layout also works without configuration changes.

If the site shows a 404, confirm that `index.html` is at the repository root and the Pages source is `main` / `/(root)`. Check the repository's **Actions** tab for deployment errors.

Official documentation:

- [GitHub Pages quickstart](https://docs.github.com/en/pages/quickstart)
- [Configuring the publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## Files and maintenance

| File | Purpose |
| --- | --- |
| `index.html` | Biography, research interests, and contact information |
| `research.html` | Research themes and related papers |
| `publications.html` | All 8 preprints and 10 journal papers listed in the supplied CV |
| `assets/styles.css` | Shared desktop, mobile, and print styles |
| `assets/portrait.png` | Portrait extracted from the supplied CV |
| `.nojekyll` | Disables Jekyll processing when included in the repository |

To update text, edit the appropriate HTML file on GitHub and click **Commit changes**. To add a paper, copy an existing `<li class="publication">` block within the appropriate section in `publications.html`, update its content and identifier, and commit. Publication numbering is automatic. Highlight Xiaoshui Lin in author lists using `<strong>Xiaoshui Lin</strong>`.

Replace `assets/portrait.png` to update the photograph. Shared profile and navigation text is present in each of the three HTML files; update all three when changing an appointment, email, or navigation label.

## Content notes

- The supplied CV is the source for appointments, education, author lists, paper titles, identifiers, and publication categories. Its original publication/preprint ordering is preserved.
- Biography and research descriptions are editorial summaries of the CV and the listed paper topics. The current focus on designing schemes for entanglement-enhanced quantum sensing was supplied by the owner.
- The Google Scholar link points to the supplied profile, using its English interface. The profile could not be read during preparation, so no citation metrics or additional papers were imported and publication statuses were not independently refreshed.
- The portrait was extracted directly from the supplied PDF. The site does not include a CV page or a downloadable CV; the HTML biography omits gender and year of birth.
- The layout takes inspiration from the supplied academic homepage example; this is an original HTML/CSS implementation. No third-party template code or photographs were copied.
- No analytics, cookies, external fonts, or JavaScript are required.

The website files are prepared for publishing. They do not establish a public GitHub Pages deployment until uploaded to a repository and enabled in Pages settings.
