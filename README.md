---
noteId: "2bda2cd0b9b111eaa214a3ec0b5026d0"
tags: []

---

**Try to port the original work to work with new version of Jupyter**

**NOT YET FINISHED!!!**

# jupyterlab_rootjs

jupyter lab support for CERN ROOT JS


## Prerequisites

* JupyterLab

## Installation

For a development install (requires npm version 4 or later), do the following in the repository directory:

```bash
npm install
npm run build
jupyter labextension link .
```

To rebuild the package and the JupyterLab app:

```bash
npm run build
jupyter lab build
```

