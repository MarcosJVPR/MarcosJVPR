<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg" />
  <img alt="Marcos Pérez — Fullstack Developer" src="assets/banner-light.svg" />
</picture>

## Hi 👋 I'm Marcos, a fullstack developer in Madrid.

React, TypeScript and Node on the front, Python and PostgreSQL behind it. I like problems where the hard part is not the interface: reconciling five messy public data sources into one schema, keeping an app usable with no connection, making a model admit when it does not know something.

<img src="assets/roles.svg" alt="Fullstack developer · React and Three.js · Python and PostgreSQL · Exploring cybersecurity" width="100%" />

**Open to fullstack roles in Madrid or remote.**
[Portfolio](https://portfolio-rho-nine-97.vercel.app) · [LinkedIn](https://www.linkedin.com/in/marcosjvpr/) · [perezmarcosjulio@gmail.com](mailto:perezmarcosjulio@gmail.com)

<img src="assets/onda.svg" alt="" width="100%" />

## Featured projects

**[Lente Democrática](https://lente-democratica.vercel.app)** — What your party promised, and how it actually voted.
Five official sources from the Spanish Congress normalised into one schema: roll-call votes, individual ballots, terms, speeches and bills. The vote JSONs identify deputies by name only, so identity resolution runs as a cascade — alias, then trigrams, then an LLM, then a human review queue. The ideological map ships with a permutation test, and the promise-coherence findings stay hidden until data coverage passes 35%.
`React 18` `Vite` `Supabase` `Python` `PostgreSQL`

**[Zolarium](https://zolariumapp.com)** — An archetype app that works offline and ships on Google Play.
Offline-first PWA packaged as an Android TWA. The recommendation engine runs on the device and retrains itself from swipes through a Postgres function. Initial bundle cut from 426 kB to 259 kB with route-level code splitting.
[Repository](https://github.com/MarcosJVPR/Zolarium) · `React 19` `Vite` `Supabase` `Leaflet` `PWA / TWA`

**[PYME Copilot](https://ai-for-small-businesses.vercel.app)** — Upload your company documents and ask. Every answer cites its source.
A full RAG system: chunking with overlap, embeddings, and semantic search over pgvector inside Postgres rather than a separate vector database. If the answer is not in your documents, it says so instead of inventing one.
`React` `Vite` `pgvector` `Supabase` `Serverless`

**[Travel to Spain](https://travel-to-spain.vercel.app)** — Official government tourism data, finally browsable.
The public Dataestur API returns Excel, not JSON. A serverless proxy solves CORS, SheetJS parses the sheet in the browser, and 43,768 rows become per-destination charts with no backend of my own to maintain.
[Repository](https://github.com/MarcosJVPR/TravelToSpain) · `React` `React Router` `Recharts` `SheetJS` `Serverless`

**Hadas vs Ogros** — Asymmetric 3D RTS, in development.
The Sylvan Court against the Iron-Crag Clans: era progression, five biomes, faction-specific visuals, object pooling architecture. Solo developer.
`Unreal Engine 5` `Blueprints`

<img src="assets/onda.svg" alt="" width="100%" />

## The portfolio itself

[portfolio-rho-nine-97.vercel.app](https://portfolio-rho-nine-97.vercel.app) — bilingual, Solarpunk art direction, and **no templates or third-party components**. Every line of CSS, every SVG and the three GLSL shaders in the hero are written by hand.

It is also the project I have been strictest with:

- Under 1 MB on a first visit, down from 8.9 MB
- Six security headers, including a Content Security Policy with no third-party origins
- Self-hosted fonts, responsive WebP, WebGL that stops rendering when it leaves the viewport
- 28 tests, run by CI on every push

## Stack

<img src="assets/stack.svg" alt="Frontend: React, TypeScript, Vite, Tailwind, Three.js, GLSL. Backend: Node.js, Python, Flask, PostgreSQL, Supabase, pgvector. Infra: Vercel, Docker, GitHub Actions, Azure CI/CD, Bash. Testing: Vitest, Testing Library, Playwright." width="100%" />

Spanish native, English C2. I came to code from a master's in marketing and branding, which is why I care more than average about whether the thing is actually understandable to the person using it.
