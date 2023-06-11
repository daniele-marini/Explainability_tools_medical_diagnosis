<a target="_blank" href="https://colab.research.google.com/github/daniele-marini/Explainability_tools_medical_diagnosis/blob/main/Grad_CAM.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

# Explainability tools medical diagnosis
Project work for the MAI4CAREU organization, done in collaboration with University of Cyprus.

![image](https://github.com/daniele-marini/Explainability_tools_medical_diagnosis/blob/main/black-box.png)

Understading the behaviour behind a machine learning model is extremely useful for many reasons:
* enhance the trust and the confidence of the users
* allow us to identify issues of the model
* identify biases in the dataset

# Authors
* Daniele Marini
* Luca Reggiani
* Asfa Jamil

# Task Description
 The main purpose of the project is to explore different techniques for explaine black-box models used for medical diagnosis. 
 For our project we explored the following techniques:
 * Model Agnostic techniques
    * LIME
    * SHAP
* Case based Reasoning Techniques
    * Case-based Ensemble Learning System
    * Visual Case-Based Reasoning Approach
* Backpropagation-based techniques
    * Grad-CAM
        * CAM
        * Score-CAM
    * DeepLIFT

# Experimental Analysis
In addition we tested the localization ability of Grad-CAM on a model fine-tuned by us

## Experimental setup
We conducted an experiment with the objective of testing the impact of utilizing Grad-CAM in the context of our study. To achieve this, we applied Grad-CAM to ResNet50 , a widely used convolutional neural network architecture.

# Model and Dataset

The model used for the classification is ResNet50, which has been fine tuned by using the "Brain MRI images for brain tumor detection" [dataset](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection).

# Results
The results of the experiment were highly satisfactory, demonstrating a remarkable ability to accurately localize the tumor's exact region as we can see in figure below.

![image](https://github.com/daniele-marini/Explainability_tools_medical_diagnosis/blob/main/comparison.png)



