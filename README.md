# Multimodal Data Integration in Computational Pathology

Explored the classification of FTIR spectra and H&E images from a limited dataset of 50 breast tissue cores. Binary classification problem where cores are either malignant (1) or non-malignant (0).

### FTIR Spectra Classification

* File: ftir_spectra_classifier_adaboost.ipynb
* Comparison of AdaBoost and Random Forests for spectra classification
* Trained a final AdaBoost model using 5-fold stratified cross validation to classify spectra from 50 breast tissue cores 
* Classification at spectra-level and core-level

### H&E Image Classification

* File: he_patch_classifier_cnn.ipynb
* Trained a CNN model using 5-fold stratified cross validation to classify breast tissue cores H&E images
* Patch-based CNN model with Multiple Instance Learning
* Classification at patch-level and core-level

### FTIR Image Classification

* File: ftir_image_classifier.ipynb
* Explored the use of a CNN model to classify breast tissue cores FTIR images

### FTIR Image Segmentation

* File: ftir_image_segmentation.ipynb
* Explored the use of U-Net for semantic segmentation of breast tissue core FTIR images
