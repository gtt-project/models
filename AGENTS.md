# AGENTS.md

GTT's data model node, published at https://models.gtt-project.org by [datamodels-toolkit](https://github.com/geolonia/datamodels-toolkit).

## Setup

- Nothing to install: the commands run with `npx github:geolonia/datamodels-toolkit#v0.3.6` (Node.js 24 or later).
- Build: `npx github:geolonia/datamodels-toolkit#v0.3.6 build` (into `_site/`).
- Move to a newer toolkit: `npx github:geolonia/datamodels-toolkit#v0.3.6 upgrade`.

## Test

- Check: `npx github:geolonia/datamodels-toolkit#v0.3.6 check` (also runs on every pull request).

## Constraints

- All changes through pull requests.
- Sign off every commit (`git commit -s`).
- Plain English.
- Published IRIs and versioned files do not change: `node.yaml`'s base URL and IRI form stay as they are, and a changed model gets a new subject version (`datamodels bump`).
- Models build on datamodels.jp where they can (`datamodels extend`). Terms that differ between Redmine instances (trackers, custom fields) stay in each instance's own @context, not here.
