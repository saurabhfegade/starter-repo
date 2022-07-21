# Frontend Starter Repo Template

Use this template to kickstart any frontend repo.

### Features

- NextJS
- TypeScript
- ESLint setup with Airbnb config
- Husky git hooks
- Cypress and RTL support for tests

### Requirements

- Node.js 14+ and npm

### Getting started

For the development server:

```shell
npm run dev
```

### Deploy to production

To see the production build locally:

```shell
$ npm run build
$ npm run start
```

### Commit messages format based on commitlint

**Format**: git commit -m "type: subject"

| Type      | Description |
| ----------- | ----------- |
| fix   | A bug fix        |
| feat   | A new feature        |
| style   | Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)        |
| refactor   | A code change that neither fixes a bug nor adds a feature        |
| chore   | Other changes that don't modify src or test files        |
| test   | Adding missing tests or correcting existing tests        |
| docs   | Documentation only changes        |
| build      | Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)       |
| ci   | Changes to our CI configuration files and scripts        |
| perf   | A code change that improves performance        |
| revert   | Reverts a previous commit        |

```shell
$ git commit -m "fix: api issue"
```
