# Kaggle-CareerCon-2019---Help-Navigate-Robots
This is my 1st Kaggle competition. In this project, we have helped robots recognize the floor surface that they’re standing on using data from its IMU sensors. 
The key aspect of our approach , which set it apart from others in the competition, is feature engineering with Fast Fourier transform (FFT). 
A toolbox is developed to generate various types of spectra features.
A random forest model is used to fit the training data and predict the test data.
Model performance and ‘classifier.feature_importances_’ indicator are used in feature selection.
Good performance, which ranks in top 5% in competition, can be achieved with this very simple model (which runs only a few minutes on a pc without GPU).
A few ideas for further improvement are also proposed.
