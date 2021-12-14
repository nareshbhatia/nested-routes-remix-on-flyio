# Nested Routes Remix on fly.io

Please see original repo and performance documentation here:
https://github.com/nareshbhatia/nested-routes.

## Fly Setup

1. [Install Fly](https://fly.io/docs/getting-started/installing-flyctl/)

2. Sign up and log in to Fly

   ```sh
   flyctl auth signup
   ```

3. Setup Fly. It might ask if you want to deploy, say no since you haven't built
   the app yet.

   ```sh
   flyctl launch
   ```

## Development

From your terminal:

```sh
npm run dev
```

This starts your app in development mode, rebuilding assets on file changes.

## Deployment

If you've followed the setup instructions already, all you need to do is run
this:

```sh
npm run deploy
```

You can run `flyctl info` to get the url and ip address of your server.

Check out the [fly docs](https://fly.io/docs/getting-started/node/) for more
information.
