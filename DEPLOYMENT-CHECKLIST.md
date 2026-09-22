# STILL HERE — Final GitHub Pages Deployment Checklist

Use this checklist before making the site public.

## 1. Prepare the repository

- [ ] Create a new GitHub repository for the website.
- [ ] Upload the contents of `STILL-HERE-website` to the repository root.
- [ ] Keep `index.html` at the repository root.
- [ ] Keep `404.html` at the repository root.
- [ ] Keep `.github/workflows/pages.yml` in the exact `.github/workflows/` path.
- [ ] Confirm `assets/favicon.svg`, `styles.css`, `script.js`, `robots.txt`, and `sitemap.xml` are present.

## 2. Enable GitHub Pages

- [ ] Open **Settings → Pages**.
- [ ] Under **Build and deployment**, choose **GitHub Actions**.
- [ ] Push to the `main` branch or run the workflow manually from **Actions**.
- [ ] Wait for **Deploy STILL HERE to GitHub Pages** to finish successfully.
- [ ] Open the generated Pages URL from the workflow's deployment environment.

## 3. Verify the live website

- [ ] Home page loads without console errors.
- [ ] Desktop navigation works.
- [ ] Mobile hamburger menu opens and closes.
- [ ] Every navigation anchor lands on the intended section.
- [ ] Favicon appears in the browser tab.
- [ ] The custom `404.html` appears for a deliberately invalid path.
- [ ] Website works on a phone in portrait mode.
- [ ] Website works on a desktop browser.
- [ ] Reduced-motion preference does not break the page.

## 4. Social links

Before launch, replace every placeholder social URL in `index.html` with the official project accounts.

- [ ] Official Telegram URL added.
- [ ] Official X URL added.
- [ ] Any future social links verified by opening them directly.
- [ ] No personal or unrelated accounts are linked.

## 5. SEO and sharing

- [ ] Replace the temporary canonical/OG URL with the final GitHub Pages domain, if one is added.
- [ ] Add the final OG/social preview image when the HERE pug artwork is ready.
- [ ] Update `sitemap.xml` with the final public URL.
- [ ] Confirm `robots.txt` points to the correct sitemap URL.
- [ ] Search the live page source and confirm the title and description are correct.

## 6. Custom domain (optional)

If a domain is purchased later:

- [ ] Add the custom domain under **Settings → Pages**.
- [ ] Configure the domain's DNS records exactly as GitHub instructs.
- [ ] Wait for DNS propagation.
- [ ] Enable **Enforce HTTPS** once available.
- [ ] Update canonical, Open Graph, X metadata, `sitemap.xml`, and `robots.txt` to the custom domain.

## 7. Final content check

- [ ] Final HERE pug artwork inserted.
- [ ] Artwork is compressed and appropriately sized for web use.
- [ ] No placeholder copy remains.
- [ ] No placeholder social URLs remain.
- [ ] `$HERE` remains clearly marked **COMING SOON** until the token actually exists.
- [ ] No invented contract address is published.
- [ ] No claims of guaranteed returns or financial outcomes are present.
- [ ] Lore and branding are consistent: **STILL HERE / $HERE / HEREVERSE**.

## 8. Recommended launch sequence

1. Deploy the website privately/test it.
2. Create the official social accounts.
3. Add the real social links.
4. Add the final pug artwork and social preview image.
5. Build the Telegram/community presence.
6. Publish the first HEREVERSE lore posts.
7. Grow the community before announcing a token launch.
8. Only then finalize token/distribution details and update the `$HERE` section.

## 9. GitHub Actions troubleshooting

If deployment fails:

- Open **Actions → Deploy STILL HERE to GitHub Pages**.
- Read the first failed step rather than rerunning repeatedly.
- Confirm Pages is set to **GitHub Actions**.
- Confirm the workflow exists on the `main` branch.
- Confirm the repository's Pages workflow has permission to deploy.
- Re-run the workflow after correcting the issue.

## Final launch test

Open the live URL on:

- Chrome desktop
- Safari/iPhone or another mobile browser
- Android Chrome
- A private/incognito window

Then test: **home → story → timeline → mystery → $HERE → community → 404**.

The site is ready when every path works and no placeholder content remains.
