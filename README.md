# Automatic segmentation of brain tumors on structural magnetic resonance imaging with deep convolutional neural networks

<p align="center">
  <img src="https://raw.githubusercontent.com/Qsinap/Brain-tumors-segmentation/56f502b8df4c9d30b4bc0c479d6dc82361c5f733/Figures/IconBrain.svg">
</p>

# Table of Contents
1. [Abstract](#abstract)
2. [Methodology](#methodology)
3. [Results](#results)
4. [Codes](#codes)
5. [Citation](#citation)

## Abstract

The analysis of medical images to explore brain tumors has gained relevance in recent years with structural magnetic resonance imaging. Although the first approaches to automated analysis of such images date back several decades, recent deep learning methods have grown exponentially in recent years, which are more efficient, more accurate, and more generalizable than conventional computer vision methods. Recent studies have focused on designing new architectures and more efficient loss functions to segmentation brain tumors. Therefore, in this article, we study the seven most novel architectures' segmentation based on the five most common loss functions. The performance of the networks was validated with the metrics of Dice coefficient, sensitivity, and specificity. It was found that the DenseNet network presented the highest score together with the Tversky focal loss function, reaching a Dice coefficient of 94.72%. The value is the highest reported so far in the segmentation of brain tumors. Furthermore, our approach was carried out with two different resolution databases, where a significant difference was observed with higher scores for the higher resolution images.

## Methodology

We propose a comparative study to determine the most efficient convolutional neural network in brain tumor segmentation on structural magnetic resonance imaging. Our approach is based on the study of the seven most common and novel CNN architectures. Besides, we also evaluate their performance with the latest loss functions. The models are trained and validated with two data sets of different resolutions.

## Results

Segmentation of the seven networks trained with the [Brain Tumor Dataset](https://figshare.com/articles/dataset/brain_tumor_dataset/1512427)

<p align="center">
  <img src="https://raw.githubusercontent.com/Qsinap/Brain-tumors-segmentation/ef5ecc652b57ee9f4a10e23233e11031039cc88d/Figures/Figure%207a.svg">
</p>

Segmentation of the seven networks trained with [The Cancer Genome Atlas Low-Grade Glioma](https://wiki.cancerimagingarchive.net/display/Public/TCGA-LGG)

<p align="center">
  <img src="https://raw.githubusercontent.com/Qsinap/Brain-tumors-segmentation/ef5ecc652b57ee9f4a10e23233e11031039cc88d/Figures/Figure%208a.svg">
</p>

## Codes
The implemented codes are made available to the public in the following link [Click Here](https://github.com/Qsinap/Brain-tumors-segmentation/tree/main/Codes)

## Citation

```
@article{brain tumors segmentation,
  title={Automatic segmentation of brain tumors on structural magnetic resonance imaging with deep convolutional neural networks},
  author={A. Anaya-Isaza, L. Mera-Jim\'enez and A. Ram\'{\i}rez-Oca\~{n}a},
  journal={doi},
  month={},
  year={2021}
}
```
This research was supported by the research division from [INDIGO Technologies.](https://indigo.tech/)
