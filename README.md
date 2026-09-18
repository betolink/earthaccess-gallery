# earthaccess gallery

A collection of Jupyter notebooks demonstrating the
[earthaccess](https://github.com/earthaccess-dev/earthaccess) Python library for
NASA Earthdata search, access, and analysis.

Try it in your browser without installing anything!

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/betolink/earthaccess-gallery/main?labpath=index.md)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/betolink/earthaccess-gallery/blob/main/notebooks/stac/odc-stac-cmr.ipynb)

> [!NOTE]
> The Binder image builds from `pixi.toml` via `binder/postBuild`. The
> `binder/runtime.txt` pins Python 3.13 so that the `earthaccess[widgets]` extra
> (lonboard / anywidget, used by `granule.explore()`) is available. Colab is a
> pip-only environment and installs from `requirements-colab.txt`.

See **[index.md](index.md)** for the full notebook list with per-notebook
**Binder** and **Open in Colab** launch buttons.

## Local development

This project uses [pixi](https://pixi.sh):

```bash
pixi install
pixi run lab
```

The `notebooks/legacy` directory contains retired notebooks that are no longer
maintained and are intentionally not linked from this gallery.
