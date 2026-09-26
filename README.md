# joshwhitk.github.io

A static Construct game export served from a GitHub Pages-style repository.

## Scope and status

- index.html loads the generated Construct runtime under scripts/. This repository is a playable/exported build rather than the editable Construct authoring project.
- Serve the files over HTTP for local inspection; service workers and media behavior can differ when opening a file directly.

## Local development

For a local HTTP preview:

```sh
python -m http.server 8000 --bind 127.0.0.1
```

Open `http://127.0.0.1:8000/`.

Documentation reviewed from source and available project history on 2026-09-27. The application was not started or acceptance-tested as part of this documentation update.
