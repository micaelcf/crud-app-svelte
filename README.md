# crud-app-svelte

The smallest honest SvelteKit CRUD: enough to show routing, data loading and component reuse, and nothing more.

## What it covers

- **Dynamic routes** — `src/routes/post/[id]/+page.svelte` with its own `+page.ts`.
- **Universal load functions** — data fetched in `+page.ts` so it runs on the server for the first paint and on the client for subsequent navigations.
- **Two reusable components** — `Table.svelte` for the list, `Dialog.svelte` for create/edit, both driven by props rather than global state.

## Stack

SvelteKit · Svelte · TypeScript · Vite

## Run it

```bash
pnpm install
pnpm dev        # localhost:5173
```

## Status

A learning reference, and complete as one. If you want a full-stack SvelteKit app, look at [roda-belem](https://github.com/micaelcf/roda-belem); if you want a CRUD API, [stash-task](https://github.com/micaelcf/stash-task).
