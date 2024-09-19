# uv-mono

This repo is an experiment on how to manage python monorepos using [uv](https://docs.astral.sh/uv/).

`path` contains path dependencies [as described in the docs](https://docs.astral.sh/uv/concepts/workspaces/#when-not-to-use-workspaces), while `workspace` uses workspaces feature.

Container images produced by both are optimized and have only the necessary resources.

Check `compose.yml` and the `Containerfile`s referenced.