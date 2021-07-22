Authorship Verification using Stylometric Regression and Classifier

This folder contains all the relevant documents and the source code of our model for Authoship Verification problem which
was our task for 6th Semester minor project (CS6490). 

Dataset:

There are two datasets in this folder: One contains the texts and the corresponding author and other contains the ground
truth which is true when two texts are written by same author otherwise it is false. Dataset are present Datasets folder.

Baseline Models:

Baseline models provide by PAN are contained in Baselines folder. For running the Baselines: Just place the dataset and notebook together, check the path of dataset in the code and run.

Model:

Our main model is minor_project_code.ipynb. We have run our model in Google Colab by mounting drive so before running our main model direclty make sure you adjust the PATH variable in minor_project_code.ipynb according to the path in your system.

Approach:

First we have used Linear Regression after finding the best param using RandomizedSearchCV. Then after that we tried Stochastic Gradient Descent classifier for training of our model. Both of these model did not give satisfactory results. Finally we tried Neural Network based model with one hidden layer which gave us the best results. 