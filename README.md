# Cross-View Gait Recognition Based on U-Net

Inspired by the great successes of GANs in image translation tasks, we propose a new gait recognition technique by using a conditional generative model to generate view-invariant features. The proposed method is evaluated on one of the largest datasets available under the variations of view, clothing and carrying conditions: CASIA gait database B. Experimental results show that the proposed method achieves an outstanding correct classification rate and outperformed state-of-the-art methods specially in carrying-bag and wearing-coat sequences. 

In this work, we propose a method of gait recognition using a conditional generative model to generate view-invariant features and overcome appearance variations due to changes of clothing, carrying conditions, and view angle. 

## Our Conditional GAN
Generator:
<center><img src='https://gitlab.com/IsRaTiAl/gait/raw/master/Images/U-Gait2.svg'/></center>

Discriminator:
<center><img src='https://gitlab.com/IsRaTiAl/gait/raw/master/Images/Discriminator3.svg'/></center>


## Some results
Original GEI representations for the subject 120 on the CASIA-B dataset. Notice that we are showing all the view-angles for three sequences: nm-01, bg-01, and cl-01.
<figure>
<center>
<img src='https://gitlab.com/IsRaTiAl/gait/raw/master/Images/Subject120OriginalGEI.png'/></center>
</figure>

Generated GEI representations for the same subject
<figure>
<center>
<img src='https://gitlab.com/IsRaTiAl/gait/raw/master/Images/Subject120GeneratedGEI.png'/></center>
</figure>

## Getting Started

You can find the notebook [here](https://gitlab.com/IsRaTiAl/gait/blob/master/Gait_U-Net_.ipynb) or open it at 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1GXSScKJ5uOJLZ-9aseO3vXLYen_DLJ9p#scrollTo=E-fqvapSsdie&forceEdit=true&sandboxMode=true)

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

## Citing

Please, cite this work as follows:

Tiñini Alvarez, Israel Raul and Sahonero-Alvarez, Guillermo, "Cross-View Gait Recognition Based on U-Net". 2020


## Acknowledgments

This work has been inspired on: 
* [Image-to-Image Translation with Conditional Adversarial Networks](https://arxiv.org/abs/1611.07004)
* [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)

## Authors
* [Israel Tiñini Alvarez](mailto:ir.tinini@acad.ucb.edu.bo)
* [Guillermo Sahonero-Alvarez](https://www.imt.ucb.edu.bo/cidimec/people/sahonero/)