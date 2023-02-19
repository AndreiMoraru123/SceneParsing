# Segmentation Architectures

## Instance segmentation for ego & alternative lanes on BDD100K

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

