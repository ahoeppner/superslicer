# SuperSlicer Configuration Files

This repository contains configuration files for SuperSlicer, a powerful and flexible slicing software for 3D printing.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Files](#files)

## Installation

To use these configuration files with SuperSlicer, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/ahoeppner/superslicer.git
    ```
2. **Navigate to the cloned directory:**
    ```bash
    cd superslicer
    ```
3. **Copy the configuration bundle to your SuperSlicer configuration directory:**
    ```bash
    cp SuperSlicer_config_bundle.ini /path/to/superslicer/config/
    ```

## Usage

1. Open SuperSlicer.
2. Go to `File > Import > Import Config Bundle`.
3. Select the `SuperSlicer_config_bundle.ini` file from this repository.

The new configurations should now be available for use within SuperSlicer.

## Files

- `SuperSlicer_config_bundle.ini`: Configuration bundle for SuperSlicer.
- `VT_300mm_bed_model.stl`: STL model for a 300mm bed.
- `VT_bed_smooth_pei.png`: Image of a smooth PEI bed.
