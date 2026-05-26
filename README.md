I recently published [`direttore`](https://www.npmjs.com/package/direttore), a zero-dependency TypeScript library for organizing API access around typed endpoints.

It was built around a few problems I kept running into across distributed and microservice-based applications: scattered auth handling, inconsistent API errors, retries, middleware, cache keys, response transforms, custom transports, and duplicated endpoint contracts spread across the app.

Direttore aims to centralize those concerns behind a typed, framework-agnostic API layer that works with plain fetch, TanStack Query, service layers, or whatever architecture best fits the project.

It tries to bring a bit of the tRPC DX to non-tRPC applications without requiring a tightly coupled stack.

It is still early, so the API may change as it gets tested against more real projects. If this is the kind of problem you also run into, give the [docs](https://github.com/caiankeller/direttore) a look, I would love feedback.

```bash
npm install direttore
```

##### If you have the means, consider [sponsoring a kid via Unbound](https://www.unbound.org).
