# Cross-View Gait Recognition Based on U-Net

In this work, we propose a method of gait recognition using a conditional generative model to generate view-invariant features and overcome appearance variations due to changes of clothing, carrying conditions, and view angle. 

![Alt text](https://gitlab.com/IsRaTiAl/gait/blob/a6e6ebff4ec9f6e10dc8f7fde63d5e1f7438b40e/Images/Subject120OriginalGEI.png?raw=true "Title")
![sdfs](https://gitlab.com/IsRaTiAl/gait/blob/a6e6ebff4ec9f6e10dc8f7fde63d5e1f7438b40e/Images/Subject120OriginalGEI.png)
## Getting Started

You can find the code at [Notebook](https://gitlab.com/IsRaTiAl/gait/blob/master/Gait_U-Net_.ipynb)

### Prerequisites

```
OpenCV
Tensorflow 2.x
Keras
```

## Built With

* [CASIA](http://www.cbsr.ia.ac.cn/english/Gait%20Databases.asp) - The dataset used
* [Pix2Pix](https://www.tensorflow.org/tutorials/generative/pix2pix) - Based on
* GoogleColab - The virtual machine used in the experiments 

## Acknowledgments

This work has been inspired on: 
* [Image-to-Image Translation with Conditional Adversarial Networks](https://arxiv.org/abs/1611.07004)
* [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)
