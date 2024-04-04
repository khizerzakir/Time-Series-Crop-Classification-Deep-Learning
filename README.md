# Time-Series Crop Classification with Deep Learning

This repository contains a Jupyter notebook demonstrating time series classification for crop identification using deep learning techniques. The dataset used in this demonstration is a subset of the MiniTimeMatch dataset.

## Dataset Information

Each observation in the dataset consists of a time series of 62 observations taken across 10 spectral bands of Sentinel-2 for 19 different classes in France. Each observation corresponds to spectral measurements aggregated over a land parcel. The observations are labeled with the crop found in the parcel.

## Reference Papers

- [Nyborg, J., Pelletier, C., Lefèvre, S., & Assent, I. (2022). TimeMatch: Unsupervised cross-region adaptation by temporal shift estimation. ISPRS Journal of Photogrammetry and Remote Sensing, 188, 301-313.](https://arxiv.org/abs/2111.02682)
- [Painblanc, F., Chapel, L., Courty, N., Friguet, C., Pelletier, C., & Tavenard, R. (2023, September). Match And Deform: Time Series Domain Adaptation through Optimal Transport and Temporal Alignment. In Joint European Conference on Machine Learning and Knowledge Discovery in Databases (pp. 341-356). Cham: Springer Nature Switzerland.](https://arxiv.org/abs/2308.12686)

## Repository References

- [TimeMatch](https://github.com/jnyborg/timematch)
- [Match And Deform (MAD)](https://github.com/rtavenar/MatchAndDeform)

## Dataset Source

The dataset used in this demonstration can be found at: [Dataset Source](https://doi.org/10.5281/zenodo.5636422)
