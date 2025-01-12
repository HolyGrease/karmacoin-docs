# Karma Coin docs

This repository contains the full source code for the Karma Coin docs web app which is available at https://karmaco.in. It is built using [Docusaurus 2](https://v2.docusaurus.io/).

## Installation

```console
yarn install
```

## Generate Sequences
Use https://github.com/seflless/diagrams

Navigate to static/seqs and run:

```console
diagrams build
```

## Local Development

```console
yarn start
```

This command starts a local development server and open up a browser window. Most changes are reflected live without having to restart the server.

## Build

```console
export NODE_OPTIONS=--openssl-legacy-provider
```

```console
yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

```console
GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
