# MTH
MTH--Matching for tumor heterogeneity--Serial whole slide image matching for tumor heterogeneity quantification.

# Paper
Title: Accurately matching serial whole slide images for tumor heterogeneity analysis.

(The paper is currently undergoing peer review, and the code and dataset will be made public later.)

# Project Overview
Malignant tumors represent a significant global health threat, and one of the key challenges in cancer treatment is tumor heterogeneity. This heterogeneity is characterized by diverse morphological and phenotypic variations within and between tumors, complicating the development of effective, individualized treatment strategies. Automating the analysis process is essential to support pathologists in accurately interpreting tumor characteristics, thereby enhancing the accuracy and efficiency of cancer diagnosis. This project focuses on the automatic matching of serial whole slide images (WSIs) to accurately quantify tumor heterogeneity, a critical factor in the reliability of personalized treatment strategies.

# Running to Match Serial WSIs

## 1. Clone the Repository:

git clone
cd serial-WSI-matching

## 2. Prepare Dataset:

The dataset can be downloaded from this link. Please ensure that the dataset path is correctly set by modifying the DatasetPath parameter to your local path.
Run the Main Script:

## 3. Run the Main Script:

Run the main_serial_WSI_matching.m command in MATLAB to start the matching process. The matching results and visualizations can be found in the results and visualization directories, respectively.

# Tumor Heterogeneity Quantification

We offer a clinical testing version of the software system that provides the following features:

## 1. Interactive Viewing of Common Regions:

Users can interactively view any common regions of interest across serial WSIs. Simply double-click on an area of interest in one WSI, and the corresponding common regions on other WSIs will be automatically visualized in the system interface.

## 2. Quantification of Tumor Heterogeneity:

The system allows users to select any shape and size of the region on any WSI. By clicking multiple times to select a closed region of interest, tumor heterogeneity can be automatically quantified. The results are visualized in the system interface to assist pathologists in analyzing cancer and guiding treatment strategies.

## 3. Demonstration

We have provided a [demonstration video](videos/Video.mp4) to further illustrate the quantifying tumor heterogeneity (see screenshot below), highlighting tumor heterogeneity quantification results to assist pathologists in developing cancer treatment strategies. For more details see the "Pathological Diagnosis" section of the main text of this paper.

![Video Thumbnail](https://github.com/WHU-lab/MTH/blob/main/videos/Software.png)

# References

```bibtex
title: Accurately matching serial whole slide images for tumor heterogeneity analysis
journal: Biomedical Signal Processing and Control
year: 2024
```

# Acknowledgments

We would like to express our sincere gratitude to the Peking University Cancer Hospital for their invaluable support and to all contributors who made this project possible.
