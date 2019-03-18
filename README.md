# Classifying-Hand-Written-Digits

In this project, I create a model for classifying hand-written digits. The digits classified are taken from the University of California, Irvine.

After explaining how hand-written digits can be stored and rendered digitally, I first classify them using a knn algorithm with cross validation, judging the algorithm's accuracy by taking the mean accuracy of the folds. I also do some hyperparameter optimizatin, trying the algorithm with different k values.

Next, I move on to a neural networks aglorithm. I begin by using a simple single-layered neural network, with cross validation, again judging the created model's accuracy by taking the mean accuracy of the folds. I try the single-layered neural network with different numbers of neurons to see which performs best. I then add second and, later, third layers to the nueral network model, still using cross validation adn varying the number of neurons each time. It is not until a three-layered neural network with 200 neurons in each layer that the accuracy of the knn algorithm is exceeded by the nueral network model.
