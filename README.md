# Data models by GTT Project

A data model node: JSON Schemas, JSON-LD @contexts and vocabularies at https://models.gtt-project.org, built with [datamodels-toolkit](https://github.com/geolonia/datamodels-toolkit) (what a node publishes: [docs/node.md](https://github.com/geolonia/datamodels/blob/main/docs/node.md)).

- `node.yaml`: the settings.
- `models/redmine/`: the first subject. A model is a folder in it with `schema.json`, `catalog.yaml` and `examples/example.json`, laid out as in [datamodels.jp](https://github.com/geolonia/datamodels/tree/main/models).
- `.github/workflows/publish.yml`: checks pull requests, and publishes main to GitHub Pages.

```bash
npx github:geolonia/datamodels-toolkit#v0.3.0 check
npx github:geolonia/datamodels-toolkit#v0.3.0 build   # into _site/
```
