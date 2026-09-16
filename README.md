# Invariant Texture Features to Gray Level Discretization

Please cite the preprint if you find this helpful: [Paper PlaceHolder]

## Overview
The key contributions of this work: 

(1)	A unified normalization framework is developed to reduce gray-level discretization dependence across multiple radiomic texture families.

(2) An analytical framework is introduced to characterize the scaling behavior of texture features, providing a systematic basis for deriving feature specific normalization factors.

(3) The proposed normalization is evaluated through complementary analyses, including ICC-based stability assessment, feature-map visualization, and an exploratory assessment of downstream classification performance.

(4) Extensive robustness experiments assess the stability of invariant features under variations in sample size and class distribution.

## Dataset
1. Brain Tumor Segmentation 2020 Dataset [BraTS 2020](https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation)
2. MR Brain Images [MALPEM-ADNI](https://www.uni-bamberg.de/en/ai/chair-of-explainable-machine-learning/software-datasets/translate-to-1-english-dataset-malpem-adni-features-binary-masks-segmentations-for-5074-adni-subjects/)
3. Cancer of the Pancreas Screening (CAPS EUS)
4. Breast Ultrasound Dataset [BUS-BRA](https://www.kaggle.com/datasets/orvile/bus-bra-a-breast-ultrasound-dataset)

## Usage
There are two subfolders under main branch.
* Invariant
  - Originial_Radiomics_Feature.ipynb: calculate original radiomic features.
  - InvariantFeatures.ipynb: calculate invariant radiomic features.
  - VisualizationMap.ipynb: generate visualization map.
  - Classification_GLCM_Features.ipynb & Classification_ALL_Features.ipynb: classificaition based on GLCM/all features.
   
* Haralick
  - Calculate Haracick GLCM features.
   
## Citations
If you find this repository useful, please consider giving a star ⭐ and citation!

## References
https://github.com/patrik-brynolfsson/invariant-haralick-features?tab=readme-ov-file
