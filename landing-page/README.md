# Landing page project

Home page for the DocBlock dapp.

## Pre-requisites

- node
- pnpm

Install packages:

```
pnpm install
```

## Development

The build process assumes the ID's of the canisters are available, so make sure you deploy the canisters first to the local replica:

```
dfx deploy
```

Then from the project root, you can run:

```
pnpm --filter landing-page run dev
```
