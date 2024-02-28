# VSFF
Codes for ***Optical and SAR Image Fusion Based on Complementary Feature Decomposition and Visual Saliency Features. (TGRS 2024)***

## Datasets
* [High-Resolution SAR and Optical Dataset](https://github.com/yeyuanxin110/YYX-OPT-SAR)<br>
* [WHU-OPT-SAR Dataset](https://github.com/AmberHen/WHU-OPT-SAR-dataset)<br>

## Citation
If this work is helpful to you, please cite it as:

```
@article{ye_2024_VSFF,
  title={Optical and SAR image fusion based on complementary feature decomposition and visual saliency features},
  author={Ye, Yuanxin and Zhang, Jiacheng and Zhou, Liang and Li, Jinjin and Ren, Xiaoyue and Fan, Jianwei},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  volume={62},
  pages={1--15},
  year={2024},
  publisher={IEEE}
}
```

## Abstract
With the expansion of optical (OPT) and synthetic aperture radar (SAR) image fusion application scenarios, it is necessary to integrate their information into land classification, feature recognition, and target tracking. Current methods focus excessively on integrating multimodal feature information to enhance the information richness of the fused images, whereas neglecting the highly corrupted visual perception of the fused results by modal differences and SAR speckle noise. To address that, this article proposes a novel optical and SAR image fusion framework named visual saliency features fusion (VSFF), which is based on the extraction and balancing of significant complementary features of optical and SAR images. First, we propose a decomposition algorithm of complementary features to divide the image into main structure features (MSF) and detail texture features (DTF). Then, for the fusion of MSF, we reconstruct the visual saliency features (VSF) maps of the pixel and structure that contain significant information from optical and SAR images, and input them into a total variation constraint model to compute the fusion result and achieve the optimal information transfer. Meanwhile, we construct a new feature descriptor based on the Gabor wavelet that separates meaningful DTF from residual noise and selectively preserves features that can improve the interpretability of the fusion result. In a comparative analysis with seven state-of-the-art fusion algorithms, VSFF achieved better results in qualitative and quantitative evaluations, and our fused images have a clear and appropriate visual perception. 

If you have any question, please email to me (swjtu_zjc@163.com).
