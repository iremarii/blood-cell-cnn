# # Blood Cell Cancer Classification Project (CNN Model)
CNN-based deep learning model for classifying cell images (Akbank Deep Learning Bootcamp project.)
# Project Goal:
This project was done as part of the "Akbank Deep Learning Bootcamp". The goal is to build a CNN-based deep learning model to classify cell images. We worked on data preprocessing, building the model, and evaluating its performance.
# Dataset
The dataset was taken from Kaggle (https://www.kaggle.com/datasets/mohammadamireshraghi/blood-cell-cancer-all-4class/data).
Uploaded by: Robin Eshraghi (Owner) and Mustafa Ghaderzadeh (Editor).
It has 4 classes: Benign, Pre-B, Pro-B, Early Pre-B.
All images were resized to 150x150 pixels for training.
# Expected Outcomes
Develop a CNN model for classification
Apply data augmentation for more data variety
Show results with Accuracy/Loss plots
Evaluate with Confusion Matrix, Classification Report, and Grad-CAM
# Methods Used
Modern CNN techniques have been used to enhance the stability and generalization ability of the model.
# Hyperparameter Optimization
The initial model showed severe overfitting (Val Loss>81). We performed optimization to fix this problem.
To mitigate this aggressive memorization, we conducted several optimization trials:

        Reduced Learning Rate: To ensure the model found the optimal solution slowly and carefully, the Learning Rate was significantly reduced from 0.001 to 0.0005, and later to a final rate of 0.0001.


# Final Results Analysis

To solve the severe overfitting problem, we gradually reduced the Learning Rate from 0.001 to 0.00001 and simplified the architecture. As a result of these efforts, our model was able to overcome memorization of the training data. The stable 70%+ Train and Validation Accuracy rate we achieved proves that the model correctly learned the patterns in the data and made reliable generalizations on new images. Considering the nature of the dataset and the limited number of images, this rate is a strong result showing that overfitting was successfully controlled.


https://www.kaggle.com/code/iremarii/brain-cell
