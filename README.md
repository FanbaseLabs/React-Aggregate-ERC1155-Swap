# React Aggregate ERC1155 Swap (Create React App)

![Modern Neon Sci-Fi Fantasy Book Cover copy](https://github.com/FanbaseLabs/React-Aggregate-ERC20-Swap/assets/145924938/277ca724-0bf4-4815-a4f9-12a26d467a69)

This repository is a minimal Create React App project that renders `aggregate-1155-swap-widget` in the main app component.

## What is in the code

- `src/App.tsx`: renders `NftExchangeWidget` from `aggregate-1155-swap-widget`.
- `src/index.tsx`: React entry point and app mount.
- `src/reportWebVitals.ts`: optional web-vitals hook from CRA.

## Install and run

```bash
npm install
npm start
```

Open `http://localhost:3000`.

## Available scripts

- `npm start`: start local development server.
- `npm run build`: create production build.
- `npm test`: run tests in watch mode.
- `npm run eject`: eject CRA configuration (irreversible).

## Widget docs

Aggregate/pure swap widget references:
https://fanbase-io.gitbook.io/docs/reference/swap-widget-sdk

Plan/app access:
https://www.plan.fanbase.io

## Notes

- Current widget configuration is in `src/App.tsx` (`appId` and `chainId`).
- If you change widget package usage in code, keep `package.json` dependencies in sync.
