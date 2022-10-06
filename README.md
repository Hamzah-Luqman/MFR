# MFR
This repoistory will contain the code of the paper **Ensemble Learning using Transformers and Convolutional Networks for Masked Face Recognition**.

# Summary
Wearing a face mask is one of the adjustments we had to follow to reduce the spread of the coronavirus. Having our faces covered by masks constantly has driven the need to understand and investigate how this behavior affects the recognition capability of face recognition systems. Current face recognition systems have extremely high accuracy when dealing with unconstrained general face recognition cases but do not generalize well with occluded masked faces. 
In this work, we propose a system for masked face recognition. The proposed system comprises two Convolutional Neural Network (CNN) models and two Transformer models. The CNN models have been fine-tuned on FaceNet pre-trained model. 
We ensemble the predictions of the four models using the majority voting technique to identify the person with the mask. The proposed system has been evaluated on a synthetically masked LFW dataset created in this work. The best accuracy is obtained using the ensembled models with an accuracy of 92\%. This recognition rate outperformed the accuracy of other models and it shows the correctness and
robustness of the proposed model for recognizing masked faces.

# Proposed models
Three main models have been proposed in this work:
## CNN models
We proposed three CNN models fine-tuned on different pre-trained models (VGG16, EfficientNet, FaceNet).  
![Alt text](cnn_models.png?raw=true)

## Transformer 
We also proposed a Transformer model for masked face recognition that uses only the encoder component. 
![Alt text](ensemble.png?raw=true)

## Ensemble model
Two approaches are used in this work for ensemble learning. The first method involves using different validation sets for each model. This method helps in overcoming the overfitting problem of the involved models. The second method is to ensemble different models with different configurations.  This helps in employing the capabilities of these models for masked face identification. In addition, combining multiple models’ predictions can reduce the variance of the resulting ensembled model. 
![Alt text](ensemble.png?raw=true)

# Dataset and models
Please follow this link to download the dataset and the trained models. 
https://drive.google.com/drive/folders/1uiTAWdU2DMyy27j3H6BPnLCiQvFRH5nD

