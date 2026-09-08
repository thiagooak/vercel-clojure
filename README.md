# vercel-clojure

Minimal Clojure web app using [http-kit](https://github.com/http-kit/http-kit), deployable to Vercel.

## Run locally

```sh
clojure -M:run
```

Then open http://localhost:8080 (or set `PORT` to something else, e.g. `PORT=3000 clojure -M:run`).

## Deploy to Vercel

This repo follows Vercel's [Dockerfile deployment](https://vercel.com/blog/dockerfile-on-vercel) support: a `Dockerfile.vercel` at the project root, listening on `$PORT`.

```sh
npm i -g vercel
vercel deploy
```
