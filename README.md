# Documentation

## Files
* Train.ipynb - Train the model
* Test.ipynb - Test the model, predict all images in a folder and save them
* Prediction.ipynb - Predict an single image, improve the quality and plot

## Folders

### Data
* data/cxr - Chest X-ray images to train
* data/masks - Chest X-ray masks to train
* data/test - Chest X-ray images for testing from same train dataset
* data/production - Chest X-ray images for testing from different dataset

### Root
* models - Model file, weights and jacard index
* predictions - Predictions from Test.ipynb
* results - Self-evaluation during train

# MultiResUNet 
#### Rethinking the U-Net architecture for multimodal biomedical image segmentation

This repository contains the original implementation of "MultiResUNet : Rethinking the U-Net architecture for multimodal biomedical image segmentation" in Tensorflow 2.

Thanks https://github.com/nibtehaz/MultiResUNet

## Paper

MultiResUNet has been published in Neural Networks

>Ibtehaz, Nabil, and M. Sohel Rahman. "MultiResUNet: Rethinking the U-Net architecture for multimodal biomedical image segmentation." Neural Networks 121 (2020): 74-87.


* [Read the Paper](https://doi.org/10.1016/j.neunet.2019.08.025)
* [View the Preprint](https://arxiv.org/abs/1902.04049)


## License
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

[MIT license](https://github.com/diego98martins/MultiResUNet-lung-segmentation/blob/master/LICENCE)
