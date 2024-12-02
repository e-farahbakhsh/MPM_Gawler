# Prospectivity Mapping of Critical Minerals in the Gawler Craton

[![DOI](https://zenodo.org/badge/510555370.svg)](https://zenodo.org/badge/latestdoi/510555370)

This repository contains the notebooks and supplementary files required to reproduce the results presented in the paper: Farahbakhsh, E., Maughan, J., Müller, R. D. (2023) Prospectivity modelling of critical mineral deposits using a generative adversarial network with oversampling and positive-unlabelled bagging, Ore Geology Reviews, 105665. The notebook enables users to create prospectivity maps for various types of mineralisation in South Australia, particularly in the Gawler Craton. The study targets three types of mineralisation: mafic-ultramafic intrusion-hosted mineralization of cobalt, chromium, and nickel.

## Input Files

The input files include geological and geophysical data, which can be downloaded via this [link](https://doi.org/10.5281/zenodo.7388657). Geological data are provided as polyline and polygon files, while geophysical data are available as points and raster layers. The polyline files contain information on faults and dykes, while the polygon files represent geological provinces and rock units. The raster layers include magnetic, gravity, radiometric, remote sensing, depth to basement, and elevation grids.

## Environment Setup

To set up the necessary environment to run the notebooks, use the `env.yml` file available in this repository. This file configures a Conda environment with all the dependencies required to run the notebooks.

Before training the models, the user needs to run the SMOTE-GAN notebook to generate synthetic positive samples.

## Output Files

The final output is a GeoTIFF file that shows the probability of the targeted mineralisation in South Australia or a specific area within it.

### Cite

```bib
@article{Farahbakhsh2023,
  title = {Prospectivity modelling of critical mineral deposits using a generative adversarial network with oversampling and positive-unlabelled bagging},
  author = {Farahbakhsh, Ehsan and Maughan, Jack and M{\"u}ller, R. Dietmar},
  year = {2023},
  journal = {Ore Geology Reviews},
  number = {105665},
  doi = {10.1016/j.oregeorev.2023.105665},
}
```
