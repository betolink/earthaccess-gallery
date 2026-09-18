# earthaccess gallery

A collection of Jupyter notebooks demonstrating the
[earthaccess](https://github.com/earthaccess-dev/earthaccess) Python library for
NASA Earthdata search, access, and analysis.

Launch any notebook in your browser — no installation required:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/betolink/earthaccess-gallery/main?labpath=index.md)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/betolink/earthaccess-gallery)
[![Open in Dev Containers](https://img.shields.io/static/v1?label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/betolink/earthaccess-gallery)

## STAC

- [cmr-to-stac](notebooks/stac/cmr-to-stac.ipynb) — convert CMR granules and collections to STAC items.
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/betolink/earthaccess-gallery/main?labpath=notebooks/stac/cmr-to-stac.ipynb)
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/betolink/earthaccess-gallery/blob/main/notebooks/stac/cmr-to-stac.ipynb)
- [odc-stac-cmr](notebooks/stac/odc-stac-cmr.ipynb) — load CMR search results as an `xarray` mosaic with `odc-stac`.
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/betolink/earthaccess-gallery/main?labpath=notebooks/stac/odc-stac-cmr.ipynb)
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/betolink/earthaccess-gallery/blob/main/notebooks/stac/odc-stac-cmr.ipynb)

## Virtual datasets

- [icechunk_virtual](notebooks/virtual-datasets/icechunk_virtual.ipynb) — virtualize granules and write / append an Icechunk store.
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/betolink/earthaccess-gallery/main?labpath=notebooks/virtual-datasets/icechunk_virtual.ipynb)
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/betolink/earthaccess-gallery/blob/main/notebooks/virtual-datasets/icechunk_virtual.ipynb)
- [virtualize_combine_tree](notebooks/virtual-datasets/virtualize_combine_tree.ipynb) — combine virtual datasets and open HDF5 groups as datatrees.
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/betolink/earthaccess-gallery/main?labpath=notebooks/virtual-datasets/virtualize_combine_tree.ipynb)
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/betolink/earthaccess-gallery/blob/main/notebooks/virtual-datasets/virtualize_combine_tree.ipynb)

## Retired

The notebooks under `notebooks/legacy` are retired, no longer maintained, and
intentionally not linked from this gallery.
