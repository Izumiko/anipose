# Anipose

[![PyPI version](https://badge.fury.io/py/anipose.svg)](https://badge.fury.io/py/anipose)

Anipose is an open-source toolkit for robust, markerless 3D pose estimation of animal behavior from multiple camera views. It leverages the machine learning toolbox [DeepLabCut](https://github.com/AlexEMG/DeepLabCut) to track keypoints in 2D, then triangulates across camera views to estimate 3D pose.

Check out the [Anipose preprint](https://www.biorxiv.org/content/10.1101/2020.05.26.117325v2) for more information.

The name Anipose comes from **Ani**mal **Pose**, but it also sounds like "any pose".

## Documentation

Up to date documentation may be found at [anipose.org](https://anipose.readthedocs.io/en/latest/) .

## Demos

https://github.com/Izumiko/anipose/assets/5195868/69eb6a69-214a-4fba-8fc9-985e3e34456f

**Videos of flies by Evyn Dickinson (slowed 5x), [Tuthill Lab](http://faculty.washington.edu/tuthill/)**

https://github.com/Izumiko/anipose/assets/5195868/d770f4c4-b0f8-4323-a234-d853c326c31f

**Videos of hand by Katie Rupp**

## References

Here are some references for DeepLabCut and other things this project relies upon:
- Mathis et al, 2018, "DeepLabCut: markerless pose estimation of user-defined body parts with deep learning"
- Romero-Ramirez et al, 2018, "Speeded up detection of squared fiducial markers"
