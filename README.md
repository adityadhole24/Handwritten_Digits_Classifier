# Handwritten_Digits_Classifier
Used a SVM Classifier to accurately classify digits from the optdigits dataset, which comprises of 8*8 images of handwritten digits. 
Used Grid Search to perform hyperparamater tuning for SVM (C, gamma and kernel).

Each digit in the dataset is represented by a 64-pixel feature vector, and the value of each feature is between 0 and 16. 
There are 10 output classes, corresponding to the digits from 0-9, thus making it a multi-class classification problem.
The train and test sets are stored in optdigits.tra and optdigits.tes respectively. These files were obtained from the UCI ML repository.
