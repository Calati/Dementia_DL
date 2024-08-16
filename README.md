# Dementia_deep_learning_project
This is a Python-based project utilizing large brain scan image datasets (approximately 100k images total) to classify the severity of Dementia with Deep Learning models. Achieving 99% test accuracy, we focused on leveraging various feature engineering methods and implementing CNN-based architectures, including transfer learning. As a leading coding contributer and the main manuscript writer in a group of 4, I implemented cleaning, feature engineering, exploratory data anlaysis, class balancing, development of more than half of our 21 unique models, model training and validation, and final model assessment.

## Python Notebooks

### dataset1_models.ipynb
This Python notebook houses our 11 models for our first dataset, ranging from traditional ML models to deeper exploration of deep learning models such as CNNs and Transfer models.

### dataset2_2d_models.ipynb 
This Python notebook houses our 6 models for our second dataset’s 2D pipeline, featuring two logistic regression models, two CNNs, and two transfer models.

### dataset2_3d_augmented_models.ipynb
This Python notebook houses our second two models for the 3D pipeline of our second dataset, focusing CNNs for stacked image volumes, or 3D images, with different types of augmentation.

### dataset2_3d_models.ipynb
This Python notebook houses our first two models for the 3D pipeline of our second dataset, focusing on CNNs for stacked image volumes, or 3D images, with class merging – one version with three classes and one version with binary classes.

## Manuscript

### Dementia_deep_learning_paper.pdf
This pdf contains the manuscript outlining our project objective, data pre-processing, model development, validation, and evaluation of performance. 

## Slides

### Dementia_deep_learning_slides.pdf
This pdf contains the powerpoint slides version of our paper, summarizing key points and ellucidating model outcomes in a visually compelling manner.

## Data Sources

### Alzheimer's MRI Pre-processed Dataset
(https://www.kaggle.com/datasets/sachinkumar413/alzheimer-mri-dataset)
This dataset, collected from several sources such as websites and hospitals, contains 6400 Preprocessed MRI Images, split into 4 classes: “Mild Demented” (896 images), “Moderate Demented” (64 images), “Non Demented” (3200 images) and “Very Mild Demented” (2240 images).

### OASIS Alzheimer's Detection 
(https://www.kaggle.com/datasets/ninadaithal/imagesoasis)
This dataset contains unprocessed MRI images from 461 patients, featuring a selection of slices that depict various sections of the brain along the z-axis. The images have been classified into 4 classes: “Mild Dementia” (5002 Images), “Moderate Dementia” (488 images), “Non Demented” (67.2k images), and “Very mild Dementia”(13.7k images).


