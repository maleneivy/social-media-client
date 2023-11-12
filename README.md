# Workflow CA

This is a course assignment I had at Noroff. The goal is to improve quality of a package by establishing helpful workflows that make the development process more efficient.

## Badges

[![Deploy static content to Pages](https://github.com/maleneivy/social-media-client/actions/workflows/static.yml/badge.svg)](https://github.com/maleneivy/social-media-client/actions/workflows/static.yml)

## Install

1. Open terminal and clone repo

```
git clone https://github.com/maleneivy/social-media-client.git
```

2. Initialize git

```
git init
```

3. Install dependencies

```
npm install
```

## Running tests

The repo is set up to run esLint and prettier with husky pre-commit.
This execute lint-stage and will check the files you´ve changed on this commit.

To run it manually:

### Eslint

```
npm run linit
```

### Prettier

```
npm run format
```

### Jest (Unit Testing)

```
npm run test-unit
```

### Cypress (E2E testing)

```
npm run test-e2e-cli
```

## Contributing

If you want to contribute to the project, follow these steps:

1. Fork the project.
2. Create a new branch "git checkout -b name-on-your-branch".
3. Make your changes and commit them "git commit -m "Your commit message".
4. Push to the branch "git push --set-upstream origin name-of-your-branch".
5. Submit a pull request.

Automated unit test and e2e test will run before the PR can be merged.
