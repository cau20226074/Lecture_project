# 20226074 final project

### Project Title
Brain Tumor Classification

### Motivation
Open_Source_SW's final project that classify brain tumor using only scikit-learn package

### Features
+ MRI data for training is given, and resized 64×64
+ model should classify whether MRI data shows Benign Tumor, Malignant Tumor, Pituitary Tumor, etc.
+ I build classifcation model using VotingClassifier containing PCA-SVM and GaussianProcessClassifier
+ and check accuracy by **cross validation**
+ and train model using **all training set**

### Installation
+ scikit-learn, scikit-image are needed
+ If those packages are missed, then, install them by using the following command
+ `pip install scikit-learn`, `pip install scikit-image`
