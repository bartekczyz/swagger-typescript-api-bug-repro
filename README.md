# `swagger-typescript-api` bug repro

1. clone this repository
2. `pnpm install` or use `npm` / `yarn`
3. run `generate` script: `pnpm genrate` or use your own package manager
4. you'll see "TypeError: Cannot create property 'consumes' on string './paths/repro.yaml#/hello'"