# Segmentation Architectures

## Instance segmentation for ego & alternative lanes on [BDD100K](https://www.bdd100k.com/)

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![PyCharm](https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green) ![nVIDIA](https://img.shields.io/badge/nVIDIA-%2376B900.svg?style=for-the-badge&logo=nVIDIA&logoColor=white)

### U-Net

U-Net was designed for biomedical data of static images in controlled environments, so it will not be suitable for fast pace road driving scenarios, but it's interesting to watch as a tool for comparison with bigger & newer architectures.

<p align="center">
  <img src="https://thumbs.gfycat.com/HandmadeShorttermAsiandamselfly-size_restricted.gif" alt="UNet" width="800" height="300">
</p>

### PSP-Net

Pyramid Scene Parsing is a module that allows the Neural Network to exploit global context information aggregated from different regions in the original image, which makes the predictions a bit more reliable, although still unusable.

<p align="center">
  <img src="https://thumbs.gfycat.com/DisloyalUnlinedAnaconda-size_restricted.gif" alt="PSP" width="800" height="300">
</p>

### DeepLabV3+

As an improvement upon its predecessor, DeepLabV3 handles segmentation at multiple scales making use of cascaded atrous (dilated) convolutions. DeepLabV3+ added a decoder as well, meant to refine the output result. 

<p align="center">
  <img src="https://thumbs.gfycat.com/ApprehensiveVacantCockroach-size_restricted.gif" alt="DeepLabV3" width="800" height="300">
</p>

### SegFormer

Using pretrained weights from ImageNet, the MIT B3 SegFormer outperforms convolutional architectures using efficient self attention on its overlapping embedded image patches

<p align="center">
  <img src="https://thumbs.gfycat.com/ForkedEducatedDragon-size_restricted.gif" alt="DeepLabV3" width="800" height="300">
</p>
