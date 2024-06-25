# Obesity-Level-Prediction-Using-Neural-Networks

**Objective**
Developed a predictive model to classify individuals into one of seven weight categories (ranging from insufficient weight to obesity type 3) based on various personal factors.

**Dataset**
Utilized a comprehensive dataset from Kaggle containing diverse features such as:
Age, Height, Smoking habits, Alcohol consumption, Frequently used modes of transportation etc.
The data was collected from people in Mexico, Peru, and Colombia.

**Models Implemented**
The following neural network architectures were implemented and compared to enhance predictive accuracy:

**1. Hybrid Models**
Combined the strengths of different neural network architectures.

**2. Feedforward Neural Network (FNN)**
Used for processing numerical and tabular data.

**3. Gated Recurrent Unit (GRU)**
Applied to categorical data for capturing sequential dependencies.

**4. Residual Networks (ResNet)**
Implemented for categorical data to improve gradient flow and model performance.

**5. Stacked Neural Network Model**
Integrated multiple layers of neural networks to improve robustness and performance.

**Project Features**
**Data Preprocessing:** Handled missing values, normalized numerical features, and encoded categorical variables.
**Model Training:** Trained various neural network models using the preprocessed data.
**Model Evaluation:** Compared the accuracy of different neural networks to identify the best-performing model.
**Result Analysis:** Analyzed and visualized the results to understand the strengths and weaknesses of each model.

**Requirements**
Python 3.7+
TensorFlow
Keras
Pandas
NumPy
Scikit-learn
Matplotlib
Kaggle API (to download the dataset)

**Results**
The accuracy of different neural network models was compared. The results showed that the hybrid models combining various architectures and stacked model 
both achieved the same accuracy in predicting obesity levels.
