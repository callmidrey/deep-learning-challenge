# deep-learning-challenge
This is my Model 21 Challenge
Analysis of Deep Learning Model

Overview of the Analysis:
The purpose of this analysis is to develop a deep learning model to address a classification problem. The dataset used for this analysis contains various features that can be utilized to predict a target variable.

## Results:

# Data Preprocessing:

Target Variable(s) for the Model:

- The target variable for the model is "IS_SUCCESSSFUL".
Features for the Model:

The features for the model include: 
    1. APPLICATION_TYPE 
    2. AFFILIATION 
    3. CLASSIFICATION 
    4. USE_CASE 
    5. ORGANIZATION 
    6. STATUS 
    8. INCOME_AMT 
    9. SPECIAL_CONSIDERATIONS 
    10. ASK_AMT

Variables Removed from Input Data:

Variables such as [list removed variables] were removed from the input data as they neither contribute to the target nor serve as features for the model.

## Compiling, Training, and Evaluating the Model:

Neurons, Layers, and Activation Functions:

The neural network model consists of 75  neurons distributed across hidden_nodes_layer1, hidden_nodes_layer2, hidden_nodes_layer3,hidden_nodes_layer4. Activation functions such as "ReLU" and "sigmoid" were chosen for their ability to capture non-linear relationships in the data.

# Achievement of Target Model Performance:

The model was able to achieve - loss: 0.5510 - accuracy: 0.7353 - 318ms/epoch - 1ms/step Loss: 0.5509999394416809, Accuracy: 0.735276997089386 close to the target performance, indicating its effectiveness in classification tasks.
Steps to Increase Model Performance:

To improve model performance, other various techniques could have been employed. These include hyperparameter tuning, feature engineering, and data augmentation.

# Summary:
In summary, the deep learning model demonstrated promising results in classification tasks. However, for further enhancement, a different model approach such as a convolutional neural network (CNN) or recurrent neural network (RNN) could be explored. A CNN is well-suited for image recognition tasks, while an RNN is effective in sequential data analysis. Depending on the nature of the dataset and the problem at hand, selecting an appropriate model architecture is crucial for achieving optimal performance.
