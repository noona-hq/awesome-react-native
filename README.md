```markdown
# Awesome React Native

A curated collection of React Native components, news, tools, and learning resources.

## Tech Stack

- **Languages:** JavaScript, TypeScript
- **Frameworks:** React Native
- **Key Dependencies:** celeste, mkdocs

## Architecture / How it works

- **Content Aggregation:** Utilizes `celeste` for aggregating and updating content in `README.md` based on configuration files.
- **Automated Updates:** Runs scheduled and pull request-based updates through GitHub Actions workflows defined in `.github`.
- **Documentation Generation:** Uses `mkdocs` to generate and publish documentation from the collected resources.
- **Static Assets:** Includes image assets like `arn.png` and `icon.svg` for branding and visual representation.

## Key interfaces / API

- **GitHub Actions Workflows:** Defined in `.github/workflows` for automating content updates and site deployment.
- **Celeste Configurations:** `celeste-config-pr.js` and `celeste-config-weekly.js` define the logic for updating the README based on different triggers.

## Dependencies

- **Noona Services:** N/A (This repository does not depend on other noona services.)
```