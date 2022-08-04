# X-ray Image Classification for Pneumonia
## Overview 
Pneumonia is an infection in one or both lungs which makes people have difficulty breathing. It can be a medical emergency, especially among high-risk groups like people over 65 and children 5 or younger, whose immune systems are relatively weaker. Therefore, it is crucial to identify pneumonia in a more efficient and accurate way, so that we can have treatment in the early stage.
## Business Problem
According to the World Health Organization, there are 156 million cases of pneumonia each year in children younger than five years. It is a serious illness, especially in young children whose immune system has not fully developed yet.

To make the diagnosis process more efficient and accurate, we're going to build  some machine learning models that are able to identify whether the input X-ray image is pneumonia or not. Once we have our model, we will cooperate with WHO, and deploy our model in some most needed areas.
## Data Understanding 
For this project, we work with 6000 chest X-ray images of pediatric patients from one to five years old found from ["Kaggle"](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia). The data has already been split into training, validation and testing sets, and all the images are labeled into two classes, either normal or pneumonia. So, we can train our model with these pre-labeled images.
## Modeling and Results
In this project, we're trying to identify whether the input image is pneumonia or not. The method we used is to build several Convolutional Neural Network (CNN) models to make the classification. We trained our model with training data and validated our models using validation data. Then based on the validation score, we choose our best model and ran that best model with testing data to get our final result. We built 12 CNN models in this project and among all the models, the model cnn7 has the best training and validation score. So we used this model as our best model and ran the test using testing data. Our best model achieved 95.7 % accuracy, 96.7 % precision and 97.3% recall.
## Conclusion & Next Step
In conclusion, our best model did a pretty good job of identifying the pneumonia images with 95.7 % accuracy, 96.7 % precision and 97.3% recall.

As for the next step, we have our best model now, so we can work with WHO and deploy our model in the real world. Meanwhile, we can keep tuning our model based on the feedback. Plus, there are a bunch of pre-trained neural network models already available online, we can run our data on those models and make some improvements to our model by comparing our model with those pre-trained models. Lastly, we don't have strong background knowledge on identifying Pneumonia, so it is necessary to tackle it with domain expertise and consult them on some questions like whether our data still has most of the features after doing image augmentation, etc. 
## Repository Contents
- Working_Notebook
- Data_split
- cnn1
- models
- .gitignore
- LICENSE.md
- model_Nntebook.ipynb
- README.md
