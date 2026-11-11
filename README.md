# Ferrocast plugins

The plugin catalog Ferrocast shows in **Settings › Plugins › Catalog**.

- `catalog.json` lists each plugin with its file's size and SHA-256.
- `catalog.json.sig` is its signature. Ferrocast checks it against the catalog key built into
  the app, and checks each file against the list before it installs it.
- `plugins/` holds the plugin files.

Every plugin here is looked at before it's added. To add or update one, see
[docs/plan/CATALOG.md](https://github.com/ArshPunisher/ferrocast/blob/own-engine-only/docs/plan/CATALOG.md)
in the Ferrocast repo.
