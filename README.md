# SvelteKit + Drizzle + SQLite

How to run:

```
yarn
yarn db:generate
yarn dev
```

How to update DB:
Update the `src/lib/db/schema.ts` file and then run the migration script

```
yarn db:migrate
```
