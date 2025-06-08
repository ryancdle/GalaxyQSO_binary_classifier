# Galaxy/QSO Binary Classification: Neural Network vs. Random Forest Classifier

In this project, I compared the performance of 2 classifiers: a Neural Network, and a Random Forest Classifier, to classify galaxies and QSOs based on features from (a sample of) the SDSS dataset.

The neural network was built from scratch using NumPy. The Random Forest Classifier was imported from the Scikit-learn library. 

Both models were optimised using Grid Search on various properties such as hyperparameters, design architectures, activation functions, etc. where applicable. 

The performance of both models were evaluated using confusion matrices, validation curves and classification reports. 
