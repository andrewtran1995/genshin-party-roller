# genshin-party

![NPM](https://img.shields.io/npm/v/genshin-party?style=flat-square)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/andrewtran1995/genshin-party/node.js.yml?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Node](https://img.shields.io/badge/Node%20js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=flat-square&logo=githubactions&logoColor=white)

Command line utility for randomly selecting team comps and other options for multiplayer fun!
* Generate a random team composition balanced around how built the characters are.
* Select a random character.
* Select a random weekly boss.

## Usage
Invoke `genshin-party` directly using `npx`.

```shell
npx genshin-party --help
```

## Contributing

Install dependencies:
```shell
yarn install
```

Run tests:
```shell
yarn test
```

Prepare files for `npm publish`:
```shell
yarn build:tsup
```