# Problem Set 1
Pneumonia Detection using CNN
Objective
The objective of this project is to develop a Convolutional Neural Network (CNN) model that can automatically classify chest X-ray images into two categories: Pneumonia and Normal.

Dataset
The dataset consists of 5,863 JPEG chest X-ray images categorized into two classes:
1.Pneumonia
2.Normal
The data is organized into three main directories:
1.train
2.test
3.val
Each directory contains subfolders for each class.
The images are anterior-posterior chest X-rays collected from pediatric patients aged between one to five years.

Methodology
1. Data Preprocessing
Image resizing (e.g., 150x150 or 224x224)
Normalization (pixel scaling)
Data augmentation (rotation, zoom, flipping) to reduce overfitting

2. Model Architecture
* Convolutional Neural Network (CNN)
* Multiple Conv2D + ReLU layers
* MaxPooling layers
* Flatten layer
* Fully Connected (Dense) layers
* Output layer with sigmoid activation (binary classification)

3. Training
* Loss Function: Binary Crossentropy
* Optimizer: Adam
* Evaluation Metrics: Accuracy, Precision, Recall

4. Evaluation
* Model evaluated on test dataset
* Confusion Matrix used to visualize performance
* Accuracy and loss curves plotted

5.Code Explanation
* Dataset loaded using image generators
* Data preprocessing handled using Keras/TensorFlow utilities
* CNN model built using Sequential API
* Model trained using training dataset and validated on validation set
* Performance evaluated using test dataset

6.Results / Findings
* The CNN model successfully learned to distinguish between Pneumonia and Normal X-rays
* Achieved high accuracy on training and validation data
* Model performance evaluated using confusion matrix and accuracy metrics

# Problem Set 2

Objective
1.The objective of this project is to predict whether a customer will subscribe to a term deposit.

Dataset
2.The dataset used is the Bank Marketing Dataset (bank-full.csv).

Methodology
1.Data preprocessing (handling categorical and numerical features)
2.One-hot encoding for categorical variables
3.Standard scaling for numerical features
4.Logistic Regression model used for classification

Code Explanation
1.Data loaded using pandas
2.Preprocessing done using ColumnTransformer
3.Model built using Pipeline
4.Model trained and evaluated using classification metrics and ROC-AUC

Results / Findings
1.The model achieved a good ROC-AUC score
2.Important features were identified using model coefficients

Conclusion
1.Logistic Regression performs reasonably well for this classification problem.
