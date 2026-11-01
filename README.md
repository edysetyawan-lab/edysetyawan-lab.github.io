# edysetyawan-lab.github.io

Personal website of Edy Setyawan, PhD. It's a plain HTML site: one page (`index.html`) plus an `images/` folder. GitHub Pages hosts it for free.

## Publish it (one time, about 10 minutes)

1. **Create a GitHub account** at https://github.com/signup. Use the username **edysetyawan**. The site address comes from the username, so the site will be at `https://edysetyawan.github.io`.
2. **Create the repository.** Click **+ → New repository**, name it exactly `edysetyawan.github.io`, set it to **Public**, and click **Create repository**.
3. **Upload the files.** On the new repository page, click **uploading an existing file**. Drag in `index.html`, `README.md` and the whole `images` folder (keep the folder name), then click **Commit changes**.
4. **Turn on Pages.** Go to **Settings → Pages**. Under *Build and deployment*, choose *Deploy from a branch*, then select branch **main** and folder **/ (root)**, and click **Save**.
5. **Wait 1–3 minutes**, then open https://edysetyawan-lab.github.io.

If the username `edysetyawan` is already taken, pick another one (for example `edy-setyawan`). Name the repository `<username>.github.io` to match. Then, in `index.html`, change the `og:image` line near the top to use the new address.

## Make changes later

Every edit can be made in the browser: open `index.html` on GitHub, click the pencil icon, edit the file, then click **Commit changes**. The live site updates within a minute or two.

- **Add a paper.** In `index.html`, find `<ol class="pubs"`. Copy one `<li>…</li>` block, paste it at the top of the list, and edit the year, title, authors, journal and DOI. Put `data-lead` on the `<li>` (as in `<li data-lead>`) when you are first author. Also update the number in `<span id="pub-count">`.
- **Add a photo.**
  1. Resize the photo to about 2000 px wide and save it as JPG at roughly 80% quality.
  2. Make a second copy about 800 px wide and add `-sm` to its file name.
  3. Upload both into `images/`.
  4. In `index.html`, find `id="gallery"`, copy one `<button …>` line, and change the file names and caption.
- **Add a portrait or team members.** Ask Claude to add the section, then upload the photos.

## Custom domain (optional, later)

Buy a domain (for example `edysetyawan.com` or a `.id` address) from any registrar. Then go to **Settings → Pages → Custom domain** and follow GitHub's DNS instructions. Hosting stays free; you pay only the yearly domain fee.
