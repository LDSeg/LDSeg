# LDSeg

--------------------

## Dataset
1. Echo (2D+t)
2. [GlaS (2D)](https://www.kaggle.com/datasets/sani84/glasmiccai2015-gland-segmentation) 
3. [knee (3D)](https://nda.nih.gov/oai/)

## Segmentation Examples
A few examples of segmentation are shown below for the Echo, GlaS and Knee datasets. Top row shows the source images/image-slices, 2nd and 3rd row shows the reverse diffusion for the latent space and the segmentation outputs. The bottom layer shows the segmentations overlay on the source images.

--------------------

### <ins> <p align='center'> Echo </ins>
![Echo](assets/EchoSeg.gif)

<br/>

### <ins> <p align='center'> GlaS </ins>
![GlaS](assets/GlaSSeg.gif)

<br/>

### <ins> <p align='center'> Knee </ins>
![Knee](assets/KneeSeg.gif)

--------------------

## Sampling Algorithms
An example of Echo segmentation for DDPM [1] and DDIM [2] sampling algorithms with 20 evenly spaced sampling steps are shown below:

--------------------

### <ins> <p align='center'> DDPM </ins>
![DDPM](assets/DDPM.gif)

### <ins> <p align='center'> DDIM </ins>
![DDPM](assets/DDIM.gif)

--------------------

## Robustness to noises
An example from each dataset is shown to demonstrate the model robustness to noise. Here, $\sigma$ is the variance of the added noise to the source image. DSC is the Dice Similarity Co-efficient score for the image (2D/3D). For the Knee dataset, a randomly selected slice is shown for convenience.

--------------------

### <ins> <p align='center'> Echo </ins>
![RobustnessEcho](assets/RobustnessEcho.gif)

<br/>

### <ins> <p align='center'> GlaS </ins>
![RobustnessGlaS](assets/RobustnessGlaS.gif)

<br/>

### <ins> <p align='center'> Knee </ins>
![RobustnessKnee](assets/RobustnessKnee.gif)

--------------------

## References

1. Ho, Jonathan, Ajay Jain, and Pieter Abbeel. "Denoising diffusion probabilistic models." Advances in neural information processing systems 33 (2020): 6840-6851.
2. Song, Jiaming, Chenlin Meng, and Stefano Ermon. "Denoising diffusion implicit models." arXiv preprint arXiv:2010.02502 (2020).

# LDSeg
