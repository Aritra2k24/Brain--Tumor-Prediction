# Brain--Tumor-Prediction using CNN

## Project Overview

A brain tumor is regarded as one of the most competitive diseases among children and adults. The majority of number one Central Nervous System (CNS) malignancies are brain tumors, which account for 85 to 90% of all CNS tumors. Every year, around 11,700 people are diagnosed with a brain tumor. Humans with a malignant mind or CNS tumor have a 5-year survival rate of around 34 percent for men and 36 percent for women. There are three types of brain tumors: start tumor, middle tumor, and end tumor. Malignant Tumor, for example, requires proper treatment, planning, and diagnostics in order to improve the patients' life expectancy. Magnetic Resonance Imaging (MRI) is a great way to detect brain cancers (MRI).
This project aims to detect brain tumors using Convolutional Neural Networks (CNN). The model is trained on a dataset of brain MRI images, which are categorized into two classes: non tumor and Tumor. The goal is to build a reliable model that can assist in diagnosing brain tumors from MRI scans.

## Objective :

Our main objective is to detect a brain tumor from MRI (Magnetic Resonance Image) using CNN (Convolutional Neural Network) .
We developed a model which is able to detect a brain tumor from MRI using CNN , we used a brain MRI data founded on kaggle.

## Dataset:

-'Dataset  : '/kaggle/input/brain-mri-images-for-brain-tumor-detection/brain_tumor_dataset'

- The Datasets contain two folder , one is 'yes' and another is 'no'.
- The folder 'yes' contain MRI that is tumous and 'no' contain non-tumous.
- We also used another folder named 'pred' folder , which is used for prediction our model.

- ## Model Achitecture:
 
- ![cnn](https://github.com/user-attachments/assets/0551518e-f048-4759-adec-ed95b57387aa)

- ## Work Flow of Proposed method:
 
- Load input data
 
- Resizing the images

- Max Pooling feature

- Adding Convolution layer

- Flattering

- Processing of the vector in dense layer

- Final dense layer applying Softmax as the Activation Function

- ## Model and Training:
  
The model consists of:
- CNN Layer
- Max Pooling Layer
- Dense Layer
- Fully Connected Layer
- Loss Function: Categorical Cross-Entropy
- Optimization Algorithm: Adam

- ## Result :
Testing is one parameter that might determine whether your work is successful or not. Testing the CNN is a key stage in the process of CNNs. Since the tests, evaluate the CNN and ensure that it is accurate How accurate are your predictions in identifying the proper result? label. Testing can also reveal issues with the CNN, such as an example of over fitting We used 80% of the data for training and 20% for analysis. for testing purposes We spent two weeks putting our CNN through its paces. different songs for it in order to find the perfect one structure and excellent precision We put the CNN to the test. different loss functions and different optimizer algorithms We experimented with different filter numbers and tried to optimize the layers. Sizes of filter.

![Screenshot 2025-07-09 101223](https://github.com/user-attachments/assets/d8b33ca7-974e-4d42-8f6d-c1cd62e265cd)

## Model Loss:
![loss](https://github.com/user-attachments/assets/54c6d6c9-e744-4dca-b674-8f6e9d638015)
 ## Model Prediction on random images from Google:
 ![Screenshot 2025-07-09 101552](https://github.com/user-attachments/assets/b25753b0-cbee-4584-b727-157f0bcd0df8)

![Screenshot 2025-07-09 101653](https://github.com/user-attachments/assets/31651b12-31b3-46a2-a798-8bad7b30d102)

## Conclusion :
Here we use CNN Classifier to classify the Brain condition using MRI Images whether it is a tumor brain or normal brain . Such technique can be used to raise the accuracy even higher and reach a level that will allow to be asset to any medical facility dealing with brain tumor.
