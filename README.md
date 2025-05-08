# GastricVision: Comprehensive Deep Learning Framework for Gastric Cancer Histopathology Image using GasHisSDB & GCHTID


![Dataset visualization](https://production-media.paperswithcode.com/datasets/a0307444-f7f3-4d34-afad-85be475dde3a.jpg)

### Authors: Annabel Chen, Deco Liu, Joyce Zhou, Jeremy Zhu 

## Introduction:
Gastric cancer remains one of the leading causes of cancer-related mortality worldwide. In 2020, gastric cancer caused approximately 800,000 deaths (accounting for 7.7% of all cancer deaths) and was the fourth leading cause of cancer deaths in both genders combined. Despite a global decline in incidence, it continues to pose a significant public health burden, especially in East Asia and South America. Early detection is critical for improving survival rates, yet the disease is often diagnosed at an advanced stage due to vague symptoms and the limitations of current diagnostic methods. Pathologically, gastric cancer is diagnosed through histological examination of biopsy samples obtained via endoscopy. Pathologists assess morphological features such as glandular architecture, cellular atypia, and invasion into surrounding tissues to confirm malignancy and determine cancer subtype. This manual process is time-consuming, subject to inter-observer variability, and dependent on expert interpretation. To support initial diagnosis, imaging techniques such as CT and PET scans are often used to evaluate tumor location, depth of invasion, and metastasis. Yet, these modalities have limited resolution for cellular-level features and must ultimately be supplemented with histopathological evaluation. Recent advances in machine learning have enabled automated systems to assist in pathology by learning discriminative features from large collections of labeled histology images. These models can support diagnosis by highlighting regions of interest, predicting cancer subtypes, and even uncovering subtle morphological patterns that may elude human observers. In this study, we used two high-quality datasets of gastric cancer histopathology images, GasHisSDB and GCHTID, which are labeled with image-level or tissue-level annotations. Together, these datasets allow us to train and evaluate deep learning models for gastric cancer with strong supervision across both binary and multiclass tissue-type classification and further unsupervised learning tasks. Our project aims to develop deep learning models in classifying gastric cancer as well as tissue types and reconstructing relevant image features. Specifically, we trained multiple neural network models including CNN for binary classification, EfficientNet for tissue type classification, Autoencoder and U-Net for image reconstruction in a self-supervised manner. compress this introduction into a shorter one.


## Dataset:
Due to the image dataset being huge, I can not upload all of them to this repository. Please download the dataset to your local environment using this link: 

GasHisSDB:
https://data.mendeley.com/datasets/thgf23xgy7/2

GCHTID: 
https://figshare.com/articles/dataset/Gastric_Cancer_Histopathology_Tissue_Image_Dataset_GCHTID_/25954813 


## Teamwork Distribution:
### Jeremy HQ Zhu (hz3106@nyu.edu): ResNet-18 Classification CNN (Using GasHisSDB) 
#### Notebook: CNN(Distillation).ipynb, CNN(add layers).ipynb, CNNbasics.ipynb
#### Paper: Introduction, Data (Partial), Results (Partial), Methods (Partial)
### Presentation: Introduction, CNN model results


### Annabel Chen (sc11601@nyu.edu): U-Net Architecture (Using GasHisSDB)
#### Notebook:UNet_whole_image.ipynb, UNet_downscaled_image.ipynb, GradCam_raw_images.ipynb
#### Paper: Introduction (partial), Hypothesis, Results (Partial), Methods (Partial)
### Presentation: First UNet model results

### Deco Liu (dl3607@nyu.edu): Efficientnet multiclassification for tissue type (Using GCHTID)
#### Notebook: Multiclass.ipynb
#### Paper: Data (Partial), Results (Partial), Methods (Partial)
#### Presentation: EfficientNet model results

### Joyce Zhou (jz4391@nyu.edu): Grad-CAM (Using GCHTID)
#### Notebook:  dataset2_activate_segmentation.ipynb
#### Paper: Results (Partial), Methods (Partial), Discussion
#### Presentation: Second UNet model results

Overall workload was split relatively evenly throughout the group, with everyone contribution their own equal sized portion the code, presentation, and paper. 

