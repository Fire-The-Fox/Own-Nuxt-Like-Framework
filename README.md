# Bux - Own Nuxt-like framework

Please read [blog page](https://dev.to/firethefox/making-own-nuxt-like-framework-with-bun-1ifn) to learn more

## Before running!
Install dependencies, apply the patch
```sh
sed -i "s/this.builder.prepare();/this.builder.prepare(this.config?.dirs ?? ['public']);/" node_modules/buchta/src/buchta.ts
```

## Note
When using bun 0.6.12 and higher, disable SSR
