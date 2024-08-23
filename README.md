# Nuxt UI Storybook

## Prerequisites

* Node: v18.17.1
* MacOS: Sonoma 14.6.1
* Memory: 32 GB
* Chip: Apple M1 Max
* Node Version Manager: 0.40.0

## Steps

1. `npx nuxi@latest init nuxt-ui-storybook`
1. choose npm as package manager
1. `npx nuxi@latest module add storybook`
1. `npm run dev` resulted in [Error #1](./errors/1.md)

## Additional attempts to set up storybook

These steps are done immediately after the steps in the previous section

1. `npx storybook-nuxt init`
1. `npm run dev` resulted in [Error #2](./errors/2.md)
1. `npm install --save-dev @storybook/vue3-vite` resulted in [Error #3](./errors/3.md)
1. Upgrade all dependencies to the latest version (except @types/node)
1. `npm run dev` resulted in [Error #4](./errors/4.md)
