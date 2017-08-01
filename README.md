# Churn-Model-ANN
Churn Model prediction using Artificial Neural Networks
Scikit-learn library has been used for encoding, splitting of dataset and feature scaling.
Keras library which is a combination of tensorflow and theano has been used in creating the Artificial Neural Network for the Churn Model.
The above mentioned libraries are the basic requirements.
Tunning has been applied to the model, using K-Cross Validation.
The code was run on spyder, after installing theano, tensorflow and Keras libraries.

NOTE: I ran the code on windows, on which keras isn't allowed to run multiple processors, therefore, "n_jobs = 1" has been used.
If you have a different system, "n_jobs = -1" can be used to further improve the efficiency and probability for the entire model.
