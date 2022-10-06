# MFR
This repoistory will contain the code of the paper **Ensemble Learning using Transformers and Convolutional Networks for Masked Face Recognition**.

# Summary
Wearing a face mask is one of the adjustments we had to follow to reduce the spread of the coronavirus. Having our faces covered by masks constantly has driven the need to understand and investigate how this behavior affects the recognition capability of face recognition systems. Current face recognition systems have extremely high accuracy when dealing with unconstrained general face recognition cases but do not generalize well with occluded masked faces. 
In this work, we propose a system for masked face recognition. The proposed system comprises two Convolutional Neural Network (CNN) models and two Transformer models. The CNN models have been fine-tuned on FaceNet pre-trained model. 
We ensemble the predictions of the four models using the majority voting technique to identify the person with the mask. The proposed system has been evaluated on a synthetically masked LFW dataset created in this work. The best accuracy is obtained using the ensembled models with an accuracy of 92\%. This recognition rate outperformed the accuracy of other models and it shows the correctness and
robustness of the proposed model for recognizing masked faces.



# Dataset and models
Please follow this link to download the dataset and the trained models. 
https://drive.google.com/drive/folders/1uiTAWdU2DMyy27j3H6BPnLCiQvFRH5nD

