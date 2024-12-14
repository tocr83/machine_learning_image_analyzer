# machine_learning_image_analyzer
A project for analyzing clothing images using machine learning and deep learning.
The project retrieves image data from a clothing company composed of ten different categories of clothing. Each image is a 28x28 pixel image.
1. The project first selects out four different categories of clothing.
2. It then truncates the set of features variables from 784 to 10 using principal component analysis. The first two principal components explain 47 per cent of the variability in the dataset and the first three explains more than 55 per cent.
3. We plot the principal components to the different clothing images by category to reveal patterns in the correlation.
4. Subsequently we select a random forest, XG boost and logistic regression classification machine learning model to predict clothing types on unseen data. For the random forest we try out 100 different models using various hyperparameter combinations.
5. Lastly, we train and deploy a deep learning neural network model with two hidden layers composed of 300 and 100 neurons with ReLu activation functions to predict the data.
