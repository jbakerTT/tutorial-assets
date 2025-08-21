# Image Assets for TT-NN and TT-Metalium Tutorials

This repository contains image assets used in the documentation and tutorials for **TT-NN** and **TT-Metalium**.

## Purpose

The images stored here support various materials, including:
- **TT-NN documentation** and [tutorials](https://docs.tenstorrent.com/tt-metal/latest/ttnn/ttnn/tutorials.html)
- **TT-Metalium documentation**

## Related Resources

- **TT-Metal Repository:** [https://github.com/tenstorrent/tt-metal](https://github.com/tenstorrent/tt-metal)
- **TT-Metalium Documentation:** [https://docs.tenstorrent.com/tt-metal/latest/tt-metalium/index.html](https://docs.tenstorrent.com/tt-metal/latest/tt-metalium/index.html)
- **TT-NN Documentation:** [https://docs.tenstorrent.com/tt-metal/latest/ttnn/](https://docs.tenstorrent.com/tt-metal/latest/ttnn/)
- **TT-NN Tutorials:** [https://docs.tenstorrent.com/tt-metal/latest/ttnn/ttnn/tutorials.html](https://docs.tenstorrent.com/tt-metal/latest/ttnn/ttnn/tutorials.html)

## Adding new assets

This repository uses **Git Large File Storage (LFS)** to efficiently manage image assets. You must have Git LFS installed to properly clone, add, and work with the files in this repository.

### Installing Git LFS

#### macOS

```bash
brew install git-lfs
git lfs install
```

#### Ubuntu/Debian

```bash
sudo apt-get update
sudo apt-get install git-lfs
git lfs install
```

### Tracking New File Types

To ensure new image formats are stored with LFS, add them to tracking:

```bash
git lfs track "*.png" "*.jpg" # add other formats as needed
```

All tracked file types are listed in the `.gitattributes` file. Make sure to commit this file after running the tracking command.

> [!NOTE] 
> If `Git LFS` is not installed, cloning this repository will only fetch small pointer files instead of the actual images.

## License

Copyright 2025 Tenstorrent AI ULC.  Licensed under Creative Commons Attribution 4.0 International Public License.
