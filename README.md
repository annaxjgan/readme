# COMP90049 Assignment 2: Predicting Supreme Court Rulings with Machine Learning
#### The goal of this project is to build and critically analyse some supervised Machine Learning models, to predict the outcome of Supreme Court Ruling based on court case metadata and text-based court discussion.

#### Steps of implementation
1. Firstly, the related Python libraries are introduced, including pandas, sklearn and Matplotlib

2. Visualise the data and distribution of features in the training and validation dataset

3. Read the training, verification and test data, and add the label of training and verification data to the training data to facilitate the later training.

4. TF-IDF is used to engineer features from the raw court text discussion, one-hot encoding is used to convert all categorical variables into feature vectors suitable for model training. Bag of Words approach is used to count the frequency of judge political orientation.

5. Use Baseline, Random Forest and Logistic Regression models to train the training data, verify with the verification data, and finally predict the test data. 

6. Results of validation data are presented and compared. Hyperparameter tuning is performed to optimise the models is evaluated based on the learning curve.

7. The datasets are also combined with post-decision features like decision date and majority ratio to explore their impact on model performance. Features associated with judge attributes are also added to the dataset to explore any bias of the political breakdown on model performances.
