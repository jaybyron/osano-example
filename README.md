This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
pnpm install

pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Osano Hydration Error

This app demonstrates the reproducible hydration error when loading the Osano script using `next/script` with the `beforeInteractive` loading strategy.

- We add the script to the root layout of the application so that it loads on all pages
- Once the app is up and running locally, when navigating to http://localhost:3000 you can see hydration error in your dev tools