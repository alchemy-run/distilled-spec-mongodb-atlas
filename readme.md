# distilled-spec-mongodb-atlas

A git mirror of Mongodb-atlas's API spec. The spec is fetched and committed as a JSON file so the repo serves as a versioned snapshot.

The mirror is updated every 24 hours and is designed to be used as a stable git submodule.

## Spec source(s)

- https://www.mongodb.com/docs/api/doc/atlas-admin-api-v2.json

## Usage as a submodule

```sh
git submodule add https://github.com/alchemy-run/distilled-spec-mongodb-atlas.git
```

## Updating specs

From `.meta/`:

```sh
bun install
bun run fetch-specs
```
