I recently published [`direttore`](https://www.npmjs.com/package/direttore), a zero-dependency TypeScript library for organizing API access around typed endpoints.

It handles a few things I kept running into across microservice projects: scattered auth headers, no shared contract, middleware, retries, status handling, cache keys, response transforms, custom transports, and consistent API errors, while staying framework-neutral enough to work with plain `fetch`, TanStack Query, service layers, or whatever else fits the app.

Direttore tries to bring a bit of the tRPC DX to non-tRPC apps.

It is still early, so the API may change as it gets tested against more real projects. If this is the kind of problem you also run into, give the [docs](https://github.com/caiankeller/direttore) a look; I would love feedback.

```bash
npm install direttore
```

##### If you have the means, consider [sponsoring a kid via Unbound](https://www.unbound.org).
