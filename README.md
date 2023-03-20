# Paradicms native

This repository contains experimental native (mobile) applications for Paradicms, implemented in React Native.


## Repository organization

* `app/`: React Native apps
* `lib/`: libraries shared between apps
* `script/`: standardized scripts for building and testing the code, following the [Scripts to Rule Them All](https://github.com/github/scripts-to-rule-them-all) pattern


## First-time setup

### Dependencies

* [Node.js 16+](https://nodejs.org/en)
* [Yarn 1.x](https://classic.yarnpkg.com/lang/en/)
* [Paradicms monorepo](https://github.com/paradicms/paradicms) checked out in a sibling directory to this repo

### Setup

```
script/bootstrap
```


## Building

## Libraries

```
yarn build-lib
```

### Libraries and apps

```
yarn build
```

## A single app

```
cd app/forms
yarn build
```

## A single library

```
cd lib/react-native
yarn build
```


## Running tests

```
script/test
```


## Continuous Integration

This repository uses [GitHub Actions](https://github.com/features/actions) for Continuous Integration and Deployment (CI/CD). See the `.github/workflows` directory for GitHub Actions workflow specifications.


## Coding conventions and tools

TypeScript code is formatted with [Prettier](https://prettier.io/).


## License

[GNU General Public License version 3 (GPLv3)](https://www.gnu.org/licenses/gpl-3.0.en.html)
