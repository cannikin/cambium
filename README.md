# Cambium

A simple photo editing app demonstrating RedwoodJS's support for React Server Components.

## Prerequisties

1. Node 20
2. Yarn 4
3. Corepack enabled

If you have `nvm` installed, you should be able to get up and running after checking out the code with:

```
nvm install 20
npm install -g yarn
corepack enable
yarn set version 4
yarn install
```

## Development

The standard Redwood dev server isn't supported yet, so in the meantime you'll need to build and serve after every change:

```
yarn rw build
yarn rw serve
```

Or the one-liner:

```
yarn rw build && yarn rw serve
```

## Usage

Select a photo and then apply simple edits supported by CSS filters.

Add your own photos to the gallery by putting them in `web/src/public/photos`. Restart your server and they should now be available for editing!
