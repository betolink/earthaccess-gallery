# earthaccess gallery

A collection of Jupyter notebooks demonstrating the
[earthaccess](https://github.com/earthaccess-dev/earthaccess) Python library for
NASA Earthdata search, access, and analysis.

## STAC

- [cmr-to-stac](notebooks/stac/cmr-to-stac.ipynb) — convert CMR granules and collections to STAC items.
- [odc-stac-cmr](notebooks/stac/odc-stac-cmr.ipynb) — load CMR search results as an `xarray` mosaic with `odc-stac`.

## Virtual datasets

- [icechunk_virtual](notebooks/virtual-datasets/icechunk_virtual.ipynb) — virtualize granules and write / append an Icechunk store.
- [virtualize_combine_tree](notebooks/virtual-datasets/virtualize_combine_tree.ipynb) — combine virtual datasets and open HDF5 groups as datatrees.

## Retired

The notebooks under `notebooks/legacy` are retired, no longer maintained, and
intentionally not linked from this gallery.
