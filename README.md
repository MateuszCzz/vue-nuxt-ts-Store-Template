# Vue Store Template

Vue open-source template for Nuxt-based Shopify Storefronts. It comes packaged with all the standard features found in a typical Shopify liquid theme, but with the added benefits of headless and Vue-powered development. This means you only need to worry about customizing the theme and not store features.

## Technologies

- [Nuxt 3](https://v3.nuxtjs.org) as the Framework
- [Storefront API](https://shopify.dev/api/storefront) as the API
- [GraphQL](https://graphql.org) to interface with the API
- [Apollo](https://www.apollographql.com) for using GraphQL
- [Pinia](https://pinia.vuejs.org) for State Management
- [Tailwind](https://tailwindcss.com) for styling
- [TypeScript](https://www.typescriptlang.org) for type safety

## Getting Started

### 1. Fork and clone this repository

### 2. Install dependencies

```zsh
npm install
# or
yarn install
```

### 3. Start developing locally

```zsh
npm run dev
# or
yarn dev
```

## Shopify Setup

> Recommended: You can sign up as a Shopify Partner to get access to development stores [here](https://www.shopify.com/partners)

1. Create a Shopify Store or login to an existing one;
2. In your store, go to apps and create a new app with Storefront API access;
3. Install the app on your store and insert the `storefront_api_access_token` into the `.env` file;
4. Insert the name of your storefront into the `.env` file.
