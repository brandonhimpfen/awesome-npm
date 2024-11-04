# Awesome npm [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome)

[![Buy Me A Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://tinyurl.com/2h9aktmd) &nbsp; [![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://tinyurl.com/d4xnrptz) &nbsp; [![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://tinyurl.com/mr22naua) &nbsp; [![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3)

> A curated list of awesome npm resources, tips, and best practices.

## Table of Contents

- [Official Resources](#official-resources)
- [Package Management](#package-management)
- [Dependency Management](#dependency-management)
- [Development Workflow](#development-workflow)
- [Publishing Packages](#publishing-packages)
- [Security](#security)
- [Performance](#performance)
- [Tooling](#tooling)
- [Tips and Best Practices](#tips-and-best-practices)

## Official Resources

- [npm Documentation](https://docs.npmjs.com/): Official documentation for npm.
- [npm CLI](https://docs.npmjs.com/cli/v7): Command-line interface (CLI) reference for npm.
- [npm Registry](https://www.npmjs.com/): Official npm package registry.

## Package Management

- [npx](https://www.npmjs.com/package/npx): Execute Node.js packages directly without installing them globally.
- [yarn](https://yarnpkg.com/): Fast and reliable package manager alternative to npm.
- [pnpm](https://pnpm.js.org/): Fast, disk space-efficient package manager that uses hard links and deduplication.
- [Verdaccio](https://verdaccio.org/): Lightweight private npm registry proxy.

## Dependency Management

- [npm-check](https://www.npmjs.com/package/npm-check): Check for outdated, incorrect, and unused dependencies.
- [npm-outdated](https://www.npmjs.com/package/npm-outdated): Check for outdated dependencies in your project.
- [npm-audit](https://docs.npmjs.com/cli/v7/commands/npm-audit): Detect and fix vulnerabilities in your dependencies.
- [dependency-cruiser](https://www.npmjs.com/package/dependency-cruiser): Analyze and visualize module dependencies in your project.

## Development Workflow

- [npm scripts](https://docs.npmjs.com/cli/v7/using-npm/scripts): Define custom scripts in the `package.json` file to automate tasks.
- [husky](https://typicode.github.io/husky/#/): Git hooks made easy for better commit messages, linting, testing, etc.
- [lint-staged](https://www.npmjs.com/package/lint-staged): Run linters on staged files before committing.
- [npm-link](https://docs.npmjs.com/cli/v7/commands/npm-link): Create symlink between projects for local development.
- [npm-run-all](https://www.npmjs.com/package/npm-run-all): Run multiple npm scripts concurrently or sequentially.

## Publishing Packages

- [Semantic Versioning](https://semver.org/): Guidelines for versioning your packages.
- [npm version](https://docs.npmjs.com/cli/v7/commands/npm-version): Bump package version according to semantic versioning.
- [np](https://www.npmjs.com/package/np): A better `npm publish` command with additional features.
- [commitizen](https://www.npmjs.com/package/commitizen): Format commit messages using a consistent style.
- [Conventional Commits](https://www.conventionalcommits.org/): A specification for adding human-readable meaning to commit messages.

## Security

- [npm audit](https://docs.npmjs.com/cli/v7/commands/npm-audit): Detect and fix vulnerabilities in your dependencies.
- [snyk](https://snyk.io/): Identify, track, and remediate vulnerabilities in open source dependencies.
- [Node Security Platform](https://nodesecurity.io/): Continuous security monitoring and vulnerability management for Node.js applications.

## Performance

- [npm ci](https://docs.npmjs.com/cli/v7/commands/npm-ci): Clean install of dependencies for faster and reliable builds.
- [Bundlephobia](https://bundlephobia.com/): Find the cost of adding an npm package to your bundle.
- [size-limit](https://www.npmjs.com/package/size-limit): Control the size of your JavaScript bundles.

## Tooling

- [nvm](https://github.com/nvm-sh/nvm): Node Version Manager for managing multiple Node.js versions.
- [npx-create](https://www.npmjs.com/package/create): Scaffold projects from any GitHub repo with a single command.
- [npm-check-updates](https://www.npmjs.com/package/npm-check-updates): Upgrade your package.json dependencies to the latest versions.
- [npm-link-shared](https://www.npmjs.com/package/npm-link-shared): Share a linked package across multiple projects.

## Tips and Best Practices

- Avoid Global Packages: Prefer local dependencies over global ones.
- Use `.npmignore`: Exclude files from being published to the npm registry.
- Scoped Packages: Use scoped packages for organization-specific modules.
- Private Packages: Publish and consume private packages within your organization.
- Avoid Deep Dependency Trees: Minimize the number of dependencies and their nested levels.

## Contribute

Contributions are welcome!

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
