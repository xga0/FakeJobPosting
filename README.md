# FakeJobPosting
Kaggle Notebook: https://www.kaggle.com/sean49/fake-job-posting-a-hybrid-nn-classifier \
A Hybrid Nerual Network Classifier with Oversample Minority Class.

## Oversample Minority Class
Since the two classes of this dataset are very imbalance, I decided to oversampling the minority class, which can be considered as adding more copies of the minority class. Here I used imblearn’s SMOTE (https://imbalanced-learn.readthedocs.io/en/stable/generated/imblearn.over_sampling.SMOTE.html) or Synthetic Minority Oversampling Technique. SMOTE uses a nearest neighbors algorithm to generate new and synthetic data for training the model.

## Model Structure
Because this dataset has a large amount of text data and several columns of categorical data, I decided to build a hybrid deep learning model. The structure of the model is as follows: 

![Model](https://raw.githubusercontent.com/xga0/fakeJobPosting/master/model_plot3.png)
