# MNIST-Digit-Recognizer-CNN-Keras-99.66

## MNIST DIGIT RECOGNIZER COMPETITION on Kaggle.

1) **The Training Dataset has 42000 Images each of 784 pixels representing Digits from 0-9.**
2) **The Test Dataset has 28000 Images.**
3) **I have reshaped the Training and the Test Samples into 28 x 28 pixels for further processing.**
4) **I have used Convolutional Neural Networks to Train the Data.**
5) **After every layer, I have used Batch Normalization to transform the data points to have Zero Mean and Variance One.**
6) **I have used Dropout layers to avoid Overfitting.**
7) **I have performed Data Augmentation and generated random images with ImageDatagenerator to avoid Overfitting.**
8) **I have used LearningRateScheduler after every Epoch to Reduce the Learning Rate in order to converge to Local Optimum.**
9) **Then, I plot the Confusion Matrix to Evaluate the Performance of the model on the data.**
10) **Lastly, I have generated csv file and made submission on Kaggle and acheived 99.66% Accuracy on its Public Leaderboard.**
