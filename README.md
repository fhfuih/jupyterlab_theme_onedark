# JupyterLab Theme OneDark

An *unofficial* port of OneDark theme for JupyterLab. I noticed that many onedark ports intentionally changes the name a little bit, say `onedork`, `halfdark`. I don't know why but, if that's related to some license issue, please remind me to change the package name!

## Prerequisites

* JupyterLab

## Installation

```bash
jupyter labextension install jupyterlab_theme_onedark
```

## Development

For a development install (requires npm version 4 or later), do the following in the repository directory:

```bash
npm install
jupyter labextension link .
```

To rebuild the package and the JupyterLab app:

```bash
npm run build
jupyter lab build
```
