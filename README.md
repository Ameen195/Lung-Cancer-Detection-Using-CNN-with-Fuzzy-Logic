# Lung-Cancer-Detection-Using-CNN-with-Fuzzy-Logic

## PROBLEM STATEMENT

In medical imaging, accurately classifying lung cancer subtypes is critical for timely and effective treatment.Traditional deep learning models may struggle with subtle variations in tumor texture and size, leading to potential misclassifications. This project integrates fuzzy logic to preprocess tumor characteristics (texture and size), assigning cancer probabilities.

## Intoduction

– Trained an Xception-based CNN to classify lung cancer images with 93%+ accuracy, using 20 epochs and optimized with EarlyStopping and ReduceLROnPlateau for enhanced performance.

– Built and deployed an end-to-end deep learning pipeline, including data augmentation, model saving, and visualization, showcasing results with matplotlib for clear accuracy/loss analysis.

– Integrated fuzzy logic preprocessing to analyze image attributes (e.g., texture, size), boosting feature quality and decision-making for cancer detection.

## Dataset

The dataset used in this project consists of lung cancer images categorized into four classes:

-Normal

-Adenocarcinoma

-Large Cell Carcinoma

-Squamous Cell Carcinoma

Dataset from Kaggle which includes Chest CT scan images - https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images

The dataset should be organized into training (train), validation (valid), and testing (test)

## THE XCEPTION MODEL ARCHITECTURE

![image](https://github.com/user-attachments/assets/ab11c12e-5dea-4f9b-b08f-7432e97141b6)

## PLOT TRAINING AND VALIDATION METRICS

![image](https://github.com/user-attachments/assets/594448aa-617e-4472-a197-55a5abed26cd)

## OUTPUT PREDICTION

![image](https://github.com/user-attachments/assets/7ae50bb2-defe-4f8f-98a0-d991d76c03f0)



