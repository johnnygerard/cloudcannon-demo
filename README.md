# CloudCannon Demo

![project status](https://img.shields.io/badge/project_status-active-success?style=for-the-badge)
[![live site](https://img.shields.io/badge/live_site-blue?style=for-the-badge)](https://tranquil-ukulele.cloudvent.net/)

## Tech Stack

### Frontend

- **Framework**: [Astro 5](https://astro.build/)
- **Styling**: [Tailwind CSS 4](https://tailwindcss.com/)

### Backend

- **Hosting**: [CloudCannon](https://cloudcannon.com/hosting/)

## How to Update

To check for outdated packages, run `npm outdated`.

```bash
# Update dependencies (this will rewrite package-lock.json and package.json)
npm update --save
npm install --save-exact --save-dev prettier@latest prettier-plugin-astro@latest prettier-plugin-tailwindcss@latest
```

## Notes

- `.nvmrc` is used primarily as a way to specify the Node.js version for CloudCannon's build environment (see [Specifying your version](https://cloudcannon.com/documentation/articles/pin-your-dependency-version/#specifying-your-version)).
- The GitHub Action `actions/setup-node@v6` relies on both `package.json` `engines` and `devEngines` to set the Node.js version and automatically cache npm dependencies.

## Dev Environment & Tools

- **System**: [Ubuntu](https://ubuntu.com/desktop)
- **Editor**: [VS Code](https://code.visualstudio.com/)
- **Formatter**: [Prettier](https://prettier.io/)
- **Linter**: [ESLint](https://eslint.org/)
- **AI assistant**: [GitHub Copilot](https://github.com/features/copilot)

## Copyright

© 2026 Johnny Gérard
