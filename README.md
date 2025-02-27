# jupyter-scribe
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jupytercalpoly/jupyterlab-richtext-mode/master?urlpath=lab/tree/notebooks/Demo.ipynb)

An extension that transforms Markdown cells into rich text-editing cells, powered by ProseMirror.

## Requirements

* JupyterLab >= 1.0.0


## Contributing

### Install

The `jlpm` command is JupyterLab's pinned version of
[yarn](https://yarnpkg.com/) that is installed with JupyterLab. You may use
`yarn` or `npm` in lieu of `jlpm` below.

```bash
# Clone the repo to your local environment
# Move to wyswiwyg-editor directory
# Install dependencies
jlpm
# Build Typescript source
jlpm build
# Link your development version of the extension with JupyterLab
jupyter labextension link .
# Rebuild Typescript source after making changes
jlpm build
# Rebuild JupyterLab after making any changes
jupyter lab build
```

You can watch the source directory and run JupyterLab in watch mode to watch for changes in the extension's source and automatically rebuild the extension and application.

```bash
# Watch the source directory in another terminal tab
jlpm watch
# Run jupyterlab in watch mode in one terminal tab
jupyter lab --watch
```


