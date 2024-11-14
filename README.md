Fractal Analysis of Retinal Images
This project applies fractal analysis techniques to retinal images to classify textures associated with retinal conditions, such as optic disc regions and exudates. The analysis focuses on computing fractal dimensions and other statistical features to distinguish between different retinal structures, which can be useful for early diagnosis of retinal diseases.

Project Overview
Objective: Use fractal analysis and machine learning classifiers to differentiate between optic disc regions and exudates in retinal images.
Dataset: Utilizes the FIVES (Fundus Image Vessel Segmentation) dataset, containing high-resolution retinal images.
Technologies Used: Python, PyCharm, scikit-image, scikit-learn, Adobe Photoshop (for manual image preprocessing).

Methodology
1.Data Preprocessing:
Manual extraction of regions (optic disc and exudates) from retinal images using Adobe Photoshop.
RGB channel separation for focused analysis.
2.Feature Extraction:
Fractal Dimension (using Differential Box Counting).
Statistical features from the Gray Level Co-occurrence Matrix (GLCM): contrast, dissimilarity, homogeneity, energy, correlation, entropy, and variance.
3.Classification:
Implemented classifiers: Random Forest, K-Nearest Neighbors, Support Vector Classifier, and Gaussian Naive Bayes.
Achieved an accuracy of 95% for all classifiers on test data.

Key Features
Extraction of fractal and statistical features from retinal images.
Classification of retinal regions using multiple machine learning algorithms.
Comparison of classifier performance with accuracy metrics and confusion matrices.

Results
Classifiers achieved up to 95% accuracy in distinguishing optic disc regions from exudates.
Notable features used for classification: fractal dimension, lacunarity, and texture measures from GLCM.