# vdruid50-gaming-front-end

Website for Streaming profile and game reviews

A hub for my Twitch channel ([VDruid50](https://www.twitch.tv/vdruid50)) and stream schedule, plus written reviews of console and mobile games.

## Tech Stack

- [SvelteKit](https://svelte.dev/docs/kit) (Svelte 5) with TypeScript
- Firebase (back end, separate repo)
- Deployed on Netlify via `@sveltejs/adapter-netlify`
- Prettier and ESLint

## Developing

Install dependencies, then start the development server:

```sh
npm install
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of the app:

```sh
npm run build
```

You can preview the production build with `npm run preview`.

## Recreating This Setup

This project was scaffolded with:

```sh
npx sv@0.17.1 create --template minimal --types ts --add prettier eslint sveltekit-adapter="adapter:netlify" --install npm .
```