# Happy Birthday Website ✦

A beautiful, interactive, and cinematic birthday celebration website with animated SVGs, custom hover sparkles, and a digital keepsake letter.

The primary entry point is [Bday.html](file:///Users/rathodpiyushmaheshbhai/Desktop/MAHI/Bday.html).

## Previewing Locally
To view the website locally on your computer:
1. Double-click the [Bday.html](file:///Users/rathodpiyushmaheshbhai/Desktop/MAHI/Bday.html) file to open it in any web browser.
2. Alternatively, use a local development server like Live Server in VS Code.

## Getting Ready for GitHub
To upload this project to GitHub:
1. Initialize Git in this directory:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: birthday website files"
   ```
2. Create a new repository on GitHub (do not initialize it with a README or license).
3. Follow the instructions on GitHub to link your local repository and push:
   ```bash
   git branch -M main
   git remote add origin https://github.com/piyushhh-04/Digital_Birthday.git
   git push -u origin main
   ```

## Deploying to Vercel or Netlify

We have configured routing rules so that both Vercel and Netlify will automatically serve [Bday.html](file:///Users/rathodpiyushmaheshbhai/Desktop/MAHI/Bday.html) as the homepage when you visit the root URL.

### Deploying to Vercel
1. Log in to [Vercel](https://vercel.com).
2. Click **Add New** > **Project**.
3. Import your GitHub repository `piyushhh-04/Digital_Birthday`.
4. Vercel will detect `vercel.json` and configure the routing automatically.
5. Click **Deploy**.

### Deploying to Netlify
1. Log in to [Netlify](https://netlify.com).
2. Click **Add new site** > **Import an existing project** (to connect to GitHub).
3. Select the repository `piyushhh-04/Digital_Birthday`.
4. Netlify will detect the `_redirects` file and configure the routing automatically.
5. Click **Deploy Site**.
