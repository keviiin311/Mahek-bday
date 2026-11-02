# Happy Birthday Website ✦

A beautiful, interactive, and cinematic birthday celebration website with animated SVGs, custom hover sparkles, and a digital keepsake letter.

The primary entry point is [Bday.html](./Bday.html). The birthday song is served from the bundled `nastelbom-happy-birthday-471481.mp3` file.

## Previewing Locally
To view the website locally on your computer:
1. Double-click [Bday.html](./Bday.html) to open it in any web browser.
2. Alternatively, use a local development server like Live Server in VS Code.

## Deploying to Vercel

1. Import the GitHub repository `keviiin311/Mahek-bday` into [Vercel](https://vercel.com/new).
2. Leave the framework preset as **Other** and the build and output settings empty; this is a static site.
3. Deploy. The [vercel.json](./vercel.json) rewrite serves `Bday.html` at the site root.
4. Each push to `main` will deploy automatically once the repository is connected.

The [Netlify `_redirects`](./_redirects) file is retained for Netlify hosting.
