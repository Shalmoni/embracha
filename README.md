# Embracha Website Starter

This is a simple static website for `embracha.com`, branded around **Embracha | Embroidery by Becky**. The current design is a no-scroll landing page based on the public Instagram profile: playful handmade keepsakes, photo hoops, nursery pieces, blessings, quotes, and colorful artsy stitching.

The site uses:

- `CNAME`
- `index.html`
- `styles.css`

It can be hosted almost anywhere because it is static HTML/CSS with no build step.

## Fastest Hosting Options

1. **Netlify**: drag this folder into Netlify Drop, then add `embracha.com` as a custom domain.
2. **Vercel**: import a GitHub repository containing these files, then add `embracha.com`.
3. **GitHub Pages**: push these files to a GitHub repository and enable Pages.
4. **GoDaddy hosting**: upload `index.html` and `styles.css` to the public web folder.

## GoDaddy DNS Basics

For GitHub Pages, publish this repository from the `main` branch and keep the included `CNAME` file set to `embracha.com`.

Then update DNS in GoDaddy:

- Use GitHub Pages' apex-domain `A` records for `@`.
- Use a `CNAME` record for `www` pointing to your GitHub Pages hostname.
- DNS updates often work within an hour, but global propagation can take up to 48 hours.

## Replace Before Launch

- Update the Instagram link if the handle ever changes.
- Update the wording if Becky wants a different one-line introduction.
