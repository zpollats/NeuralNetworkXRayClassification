# X-ray Image Classification for Pneumonia
## Overview 
Pneumonia is an infection in one or both lungs which makes people have difficulty breathing. It can be a medical emergency, especially among high-risk groups like people over 65 and children 5 or younger, whose immune systems are relatively weaker. Therefore, it is crucial to identify pneumonia in a more efficient and accurate way, so that we can have treatment at early stage.
## Business Problem

## Data Understanding 
For this project, we work with 6000 X-ray images found from ["Kaggle"](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia). The data has already been split into training, validation and testing sets, and all the images are labeled as either normal or pneumonia. So, we can train our model with these pre-labeled images.
## Modeling and Results
In this project, we're trying to identify whether the input image is pneumonia or not. The method we used is to build several Convolutional Neural Network (CNN) models to make classification. We trained our model with training data and validated our models using validation data. Then based on the validation score, we choose our best model and ran that best model with testing data to get our final result.
## Conclusion & Recommendation

## Repository Contents
- Working_Notebook
- Data_split
- cnn1
- models
- .gitignore
- LICENSE.md
- model_Nntebook.ipynb
- README.md
