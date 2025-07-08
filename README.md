# Spin Astro Starter

This is a simple [Astro](https://docs.astro.build/en/getting-started/) starter web app that runs (and deploys) as a WebAssembly app using [Spin](https://spinframework.dev/).


## Build

```
npm run build
```

Re-compiles the Astro site to the `/dist` directory. This directory can be [modified](https://docs.astro.build/en/reference/configuration-reference/#base) in the Astro config.mjs file.


## Dev

```
npm run dev
```

This runs Astro via Spin.


```
▶ src/pages/index.astro
   └─ /index.html (+3ms) 
✓ Completed in 5ms.

[build] 1 page(s) built in 311ms
[build] Complete!
Finished building all Spin components
Logging component stdio to ".spin/logs/"
Serving http://0.0.0.0:4321
```

This will serve the Astro site at [http://0.0.0.0:4321](http://0.0.0.0:4321)


## Deployment

#### Deploy to Fermyon Wasm Functions:  

Run your site via the [Fermyon Wasm Functions](https://www.fermyon.com/wasm-functions) edge service - ideal for ultra-fast performance.

```
spin aka login
spin aka deploy

Deploying app to Fermyon Wasm Functions... 
Waiting for app to be ready...
```

This will deploy and distribute your app via Fermyon Wasm Functions, which runs on Akamai's distributed compute network. Learn more in [the Docs here](https://developer.fermyon.com/wasm-functions/index#application-deployment).

Example: [https://c6ae6179-482f-4389-8ae1-61450910d5fc.aka.fermyon.tech](https://c6ae6179-482f-4389-8ae1-61450910d5fc.aka.fermyon.tech)


#### Deploy to Fermyon Cloud:

Run your site on [Fermyon Cloud](https://www.fermyon.com/cloud) - ideal for simple starter apps.

```
spin cloud deploy

Uploading spin-astro-starter version 0.0.1 to Fermyon Cloud...
Deploying...
Waiting for application to become ready........
https://spin-astro-starter-dgiqdewz.fermyon.app/
```

Example: [https://spin-astro-starter-dgiqdewz.fermyon.app](https://spin-astro-starter-dgiqdewz.fermyon.app/)

---

For more information about deploying and running Wasm apps see the [Spin Documentation](https://github.com/spinframework/spin).
