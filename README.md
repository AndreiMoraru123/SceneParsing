# Segmentation Architectures

## Instance segmentation for ego & alternative lanes on BDD100K

### U-Net

U-Net was designed for biomedical data of static images in controlled environments, so it will not be suitable for fast pace road driving scenarios, but it's interesting to watch as a tool for comparison with bigger & newer architectures.

<p align="center">
  <img src="https://user-images.githubusercontent.com/81184255/219595204-d18d37e6-51a5-4089-b3e8-ad57bea2d9c3.gif" with = "200" height = "175" />
</p>

### PSP-Net

Pyramid Scene Parsing is a module that allows the Neural Network to exploit global context information aggregated from different regions in the original image, which makes the predictions a bit more reliable, although still unusable.

<p align="center">
  <img src="https://user-images.githubusercontent.com/81184255/219856210-1dab9051-166d-45c8-9789-a9522aea2a47.gif" with = "200" height = "175" />
</p>

### DeepLabV3+

As an improvement upon its predecessor, DeepLabV3 handles segmentation at multiple scales making use of cascaded atrous (dilated) convolutions. DeepLabV3+ added a decoder as well, meant to refine the output result. 

<p align="center">
  <img src="https://user-images.githubusercontent.com/81184255/219937806-71ebe839-8c8e-470c-8b52-8ff87d069be8.gif" with = "200" height = "175" />
</p>


<video autoplay loop muted playsinline style="width:100%;">
  <source src="https://user-images.githubusercontent.com/81184255/219937806-71ebe839-8c8e-470c-8b52-8ff87d069be8.gif" type="video/mp4">
</video>
