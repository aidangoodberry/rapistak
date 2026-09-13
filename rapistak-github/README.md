# Rapistak website

A complete, editable static website with Rapistak branding, responsive navigation, product pages, industry photos, and equipment manuals.

## Upload to GitHub

1. Extract the ZIP on your computer.
2. Create a new GitHub repository, or open the repository you want to use.
3. Choose **Add file → Upload files** (or **uploading an existing file** in an empty repository).
4. Drag the extracted contents into the upload area, including the **manuals** folder. Put **index.html** at the repository root, not inside another folder. Upload the extracted files, not the ZIP itself. Include the hidden **.nojekyll** file if your file picker shows it.
5. Enter a commit message, then save the changes. For an existing repository, use a branch and merge the changes after review if appropriate.

GitHub's **Import repository** feature is for importing an existing Git repository URL; for this ZIP use **Upload files** or GitHub Desktop.

## Publish with GitHub Pages

1. In the repository, open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the branch containing these files (usually **main**) and **/(root)**.
4. Click **Save**. GitHub displays the website URL on this settings page when publishing is ready.

No build command or package installation is needed. GitHub Pages is available for public repositories on GitHub Free; private-repository availability depends on your plan. Relative links work with a project site URL such as https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/.

Use the new GitHub Pages URL for this copy. This export does not change the currently hosted website or transfer a custom domain.

## Edit the website

- **index.html** — home page
- **prostak.html**, **maxrak.html**, **leviathan.html**, **autostak.html**, **skarab.html**, **unit-supply-cargo-rack.html**, **industrial-pull-out-shelving.html** — products
- **industries.html** — eight industry sections
- **installations.html** — equipment photos
- **resources.html** — literature and video resources
- **service.html** — support information and manual links
- **style.css** — colors, typography and responsive layout
- **app.js** — dropdown and mobile navigation behavior
- **logo.png**, **favicon-brand.svg** — company branding and tab icon
- **manuals/** — PDF manuals

Each page contains its own header and footer. Apply shared navigation changes to every HTML file. Keep filenames and relative paths intact when replacing images or PDFs.

## Local preview

Open **index.html** in a browser, or run the following from this folder with Python installed:

    python -m http.server 8000

Then open http://localhost:8000/. Stop the server with Ctrl+C.

## Features and external services

The site uses plain HTML, CSS and JavaScript. It requires no ChatGPT sign-in, Sites service, API keys, database or application server. Fonts load from Google Fonts, with local font fallbacks. Video resources link to Rapistak's official YouTube channel. Sales and support buttons open an email application or phone dialer; there is no form-submission backend.

Rapistak's original website supplied the logo, product information, images and manuals. No separate open-source license is added for those brand assets.

## GitHub documentation

- [Upload files](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
- [Configure GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
