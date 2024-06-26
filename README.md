# Handwritten Digit Recognition
The project focuses on creating models to predict handwritten digits using the MNIST dataset, which consists of 60,000 training examples and 10,000 test examples of size-normalized and centered digits.

The project explores three classifier models: Random Forest Classifier, Support Vector Machines (SVM), and Neural Networks (specifically, a Convolutional Neural Network, CNN). The Random Forest Classifier, an ensemble learning method, is praised for its accuracy, versatility, and ease of use without parameter tuning, but it is criticized for being time-consuming and memory-intensive. SVM, a supervised learning algorithm, is noted for its memory efficiency and good performance on the MNIST dataset with proper hyperparameter tuning (C: Regularization and Gamma: Inverse width of Gaussian kernel), but it requires careful pre-processing and parameter tuning. The CNN is highlighted for its feature learning capabilities and performance but is considered complex and resource-intensive.

The project compares the complexity, performance, pre-processing requirements, and memory efficiency of the models. Random Forest is found to be less complex and does not require scaling or pre-processing but is memory-intensive. SVM is more complex, requires both scaling and pre-processing, but is memory-efficient. Neural Networks are very complex, require some pre-processing, and are resource-intensive.

Results show that the Random Forest Classifier achieved an accuracy of 0.9705 and an F1 score of 0.9702, while SVM reached an accuracy of 0.9792 and an F1 score of 0.9791. The CNN demonstrated the highest accuracy, with 0.9855 in the third epoch, and a loss of 0.0492.

Overall, the project successfully implemented and compared three different machine learning models for handwritten digit recognition, with the CNN emerging as the most accurate classifier among the three. The document serves as a comprehensive study of the models' capabilities and their performance on the MNIST dataset.



# Files to Download: 
In order to run the google collab notebook successfully, please ensure you download the testing & training datasets, which are called "mnist.train"  and "mnist.test" from the google drive [found here: https://drive.google.com/drive/folders/1zQDmYtzk8F0WWuujj_U748AwjGLm4SZn?usp=sharing]. These files need to be uploaded on the google notebook so that the code can run properly. It may take quite a while (typically the runtime has been around 13ish minutes since its a very large dataset).

