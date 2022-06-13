This is a [Next.js](https://nextjs.org/) project based on example code created by [idoshamun](https://github.com/idoshamun/nextjs-isr-logrocket/tree/main) - it is a simple NextJS app running on [Layer0](https://app.layer0.co) that retrieves data from random [Public APIs](https://api.publicapis.org/random) and does ISR, SSG, and SSR. The goal is to use this as a debugging tool.

## Getting Started

First, install the Layer0 CLI:
```bash
npm i -g @layer0/cli@latest
```

Install packages
```
npm i
or
yarn
``` 

Then run the Layer0 development server:
```bash
0 dev
```

Open [http://localhost:3000](http://localhost:3000) 

the `/isr` path runs NextJS ISR

the `/ssg` path runs NextJS SSG

the `/ssr` path runs NextJS SSR 

`routes.js` defines the routes and caching rules for Layer0
`layer0.config.js` defines the Layer0 connector being used (NextJS)

## Learn More

To learn more about Layer0, sign up for a free account
- [Layer0 Console](https://app.layer0.co)
- [Layer0 Documentation](https://docs.layer0.co)

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.