# Builder.io + Shopify Hydrogen - headless visual page building demo

Example repo using Builder.io for drag and drop page building with Shopify hydrogen

[Check out the hydrogen docs](https://shopify.dev/custom-storefronts/hydrogen)

See [./pages/landing/[handle].server.jsx](./pages/landing/[handle].server.jsx) for where we integrate Builder.io

## Getting started

**Requirements:**

- Node v14+
- Yarn

```bash
yarn
yarn dev
```

Remember to update `shopify.config.js` with your shop's domain and Storefront API token!

## Previewing a production build

To run a local preview of your Hydrogen app in an environment similar to Oxygen, build your Hydrogen app and then run `yarn preview`:

```bash
yarn build
yarn preview
```

## Building for production

```bash
yarn build
```

Then, you can run a local `server.js` using the production build with:

```bash
yarn serve
```
