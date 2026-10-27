# Raushani Kumari — Developer Portfolio

A responsive React + Vite portfolio for showcasing full-stack engineering, AI/ML integrations, and product development experience.

## Run locally

```bash
npm install
npm run dev
```

## Build for production

```bash
npm run build
npm run preview
```

## Publish with GitHub Pages

1. Create a new **public** repository named `raush16.github.io` in your GitHub account (`raush16`).
2. Extract this project and upload the contents of this folder to the repository root. Ensure `.github/workflows/deploy.yml` is included.
3. Commit the files to the `main` branch.
4. In GitHub, open **Settings → Pages** and set the build/deployment source to **GitHub Actions**.
5. Open the **Actions** tab and wait for “Deploy portfolio to GitHub Pages” to finish successfully.
6. Your site should then be available at `https://raush16.github.io/`.

If you use a repository with another name, update the Vite `base` setting in `vite.config.js` before deploying. The recommended `raush16.github.io` repository uses the root path and needs no extra base setting.

## Before publishing

- Review all project descriptions and remove anything your employer does not permit you to share.
- Add links to public demos or repositories only when they are available and approved for sharing.
- The resume PDF is included at `public/Raushani-Kumari-Resume.pdf`.
- The portfolio currently links to the GitHub profile `raush16`, LinkedIn profile, and email shown on the resume.
