# Brain-Tumor-Classification

## 1. INTRODUCTION

Brain tumor is the collection is an abnormal mass of tissue in which cells grow and multiply uncontrollably, seemingly unchecked by the mechanisms that control normal cells. Brain tumors can be both malignant or benign. The most common types of brain tumors are Glioma, Meningioma and Pituitary tumor. 

There are several medical imaging techniques used to acquire information about tumors (tumor type, shape, size, location, etc.), which are needed for their diagnosis. Magnetic Resonance Imaging (MRI) is one of the most used technique. These images are examined by the radiologist. A manual examination can be error-prone due to the level of complexities involved in brain tumors and their properties.

The goal of this project is to develop a Deep Learning approach by using Convolutional Neural Network and Transfer Learning (TL) to detect and classify Brain Tumor.

## 2. DATA OVERVIEW

The data set provided by https://www.kaggle.com/sartajbhuvaji/brain-tumor-classification-mri is used in this study. The dataset contains 4 subfolders which are consisted of respective tumor classes, Glioma, Meningioma, Pituitary, and No Tumor datasets.

## 3. CLASSIFICATION METHODS AND MODELS

In this project I worked on 3 different approaches. Multi-Class Classifiers Method,  Multiple Binary-Classifiers Method and Ensemble Method. 

3.1 Multi-Class Classifiers Method:

In Multi-class classification CNN models which have strong capability to capture spatial relationships of pixels across rows and columns and pre-trained models VGG-16 and RESNET50 are performed.

3.2 Multiple Binary-Classifiers Method:

In this method, the training data set is divided into 3 binary classes. In each binary classes, the data set is splitted into training, validation, and testing data sets.

3.3 Ensemble Method:

In this section the ensemble method which uses multiple learning algorithms to obtain better predictive performance than could be obtained from any learning algorithms alone, is applied by concatenating the best binary classifications models and Model_Multiclass based on the highest probability method.

## 4. Metrics and Evaluation:

The goal of this project is to detect and classify the tumor correctly. Capturing the tumor is highly important for treatment. Therefore recall score which measures the model in identifying the True Positives correctly is an important decision criteria in model evaluation. 

Although recall is crucial in tumor diagnosis and treatment, precision metric which is important to avoid improper treatment for a patient with no disease or different tumor disease, plays an important role in stakeholder’s decision. Therefore both recall and precision are calculated.


