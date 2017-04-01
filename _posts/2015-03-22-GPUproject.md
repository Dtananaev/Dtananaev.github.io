---
layout: post
title: GPU project
---
<p align="center">
  <img src="https://github.com/Dtananaev/cuda_filters/raw/master/pictures/tower_gaussn.jpg" width="350" class="teaser-img"/>
  <img src="https://github.com/Dtananaev/cuda_filters/raw/master/pictures/tower_gaussn_cunlm.jpg" width="350"class="teaser-img"/>
</p>
The GPU project contains the implementation of the non-local mean denoising filter in GPU CUDA. In the frame of the project there were developed naive version of the non-local mean filter which uses sliding window approach for filtering and volumetric kd-tree implementation for video sequences.
The source code for the naive version of the filter is available.

**Source:** [Dtananaev/cuda_filters](https://github.com/Dtananaev/cuda_filters)

The source code contains:

1. Naive Non-Local mean filter implementation
2. Color inversion 
3. Median filter for the "salt and pepper" noise


## Naive Non-Local Mean filter
<p align="center">
  <img src="https://github.com/Dtananaev/cuda_filters/raw/master/pictures/tower_gaussn.jpg" width="350" />
  <img src="https://github.com/Dtananaev/cuda_filters/raw/master/pictures/tower_gaussn_cunlm.jpg" width="350""/>
</p>
## Color inverse
<p align="center">
  <img src="https://github.com/Dtananaev/cuda_filters/blob/master/pictures/lena.jpg" width="350"/>
  <img src="https://github.com/Dtananaev/cuda_filters/blob/master/pictures/lena_inverted.jpg" width="350"/>
</p>
## Median filter
<p align="center">
  <img src="https://github.com/Dtananaev/cuda_filters/blob/master/pictures/balloons_noisy.jpg" width="350"/>
  <img src="https://github.com/Dtananaev/cuda_filters/blob/master/pictures/balloons_noisy_cumedian.jpg" width="350"/>
</p>


