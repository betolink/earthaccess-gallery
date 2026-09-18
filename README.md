# earthaccess gallery

A collection of Jupyter notebooks demonstrating the
[earthaccess](https://github.com/earthaccess-dev/earthaccess) Python library for
NASA Earthdata search, access, and analysis.

Try it in your browser without installing anything!

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/betolink/earthaccess-gallery/main)

> [!NOTE]
> The Binder image builds from `pixi.toml` via `binder/postBuild`. The
> `binder/runtime.txt` pins Python 3.13 so that the `earthaccess[widgets]` extra
> (lonboard / anywidget, used by `granule.explore()`) is available.

## Notebooks

### STAC

- [cmr-to-stac](https://mybinder.org/v2/gh/betolink/earthaccess-gallery/main?labpath=notebooks/stac/cmr-to-stac.ipynb)
  — convert CMR granules and collections to STAC items.
- [odc-stac-cmr](https://mybinder.org/v2/gh/betolink/earthaccess-gallery/main?labpath=notebooks/stac/odc-stac-cmr.ipynb)
  — load CMR search results as an `xarray` mosaic with `odc-stac`.

### Virtual datasets

- [icechunk_virtual](https://mybinder.org/v2/gh/betolink/earthaccess-gallery/main?labpath=notebooks/virtual-datasets/icechunk_virtual.ipynb)
  — virtualize granules and write / append an Icechunk store.
- [virtualize_combine_tree](https://mybinder.org/v2/gh/betolink/earthaccess-gallery/main?labpath=notebooks/virtual-datasets/virtualize_combine_tree.ipynb)
  — combine virtual datasets and open HDF5 groups as datatrees.

## Local development

This project uses [pixi](https://pixi.sh):

```bash
pixi install
pixi run lab
```

The `notebooks/legacy` directory contains retired notebooks that are no longer
maintained and are intentionally not linked from this gallery.
