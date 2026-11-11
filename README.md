# Padmini Ramesh — personal website

A single-page academic site (Home, Publications, Field Diaries, Talks, CV) built in plain HTML and CSS. No build step.

## Put it online with GitHub Pages
1. Sign in at github.com (or create a free account).
2. Click **+ → New repository**. Name it `USERNAME.github.io` (replace USERNAME with the GitHub username). Set it to **Public**. Click **Create repository**.
3. On the new repository page, click **uploading an existing file**. Drag in everything from this folder: `index.html`, `favicon.svg`, `.nojekyll`, `README.md` and the whole `photos` folder. Click **Commit changes**.
4. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
5. After a minute or two the site is live at `https://USERNAME.github.io`.

## Use your own domain (optional)
1. Buy a domain (for example `padminiramesh.com`) from any registrar.
2. In **Settings → Pages → Custom domain**, enter the domain and save.
3. At the registrar, add DNS records:
   - Four **A** records for `@` pointing to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - One **CNAME** record for `www` pointing to `USERNAME.github.io`
4. Once GitHub confirms the domain, tick **Enforce HTTPS**.

## Updating the site
- Text: open `index.html` on GitHub, click the pencil icon, edit, and commit.
- CV: upload `cv.pdf` to the repository, then change the CV links in `index.html` from `#cv` to `cv.pdf`.
- Photos: add files to `photos/` and copy an existing `<figure class="fd">` block in `index.html`.
