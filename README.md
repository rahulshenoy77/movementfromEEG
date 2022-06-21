# Classification of movement related thoughts from EEG signals 
We explore the possibilities of using deep learning techniques including Convolutional Neural Networks(CNN), Recurrent Neural Networks(RNN) such as Long Short Term Memory (LSTM), and briefly discuss the performance of Variational Autoencoders(VAE) and Generative Adversarial Networks (GAN) in the classification of movement related thoughts such as the imagination of movement of the left hand(class 1), right hand(class 2), both feet(class 3), and tongue(class 4). Architectures with Multiple layers of CNN are trained and optimized on varying data to correctly predict the task and accuracy is reported for each approach. We also considered using LSTM since the data provided consisted of observations at regular time-intervals. We use techniques of regularization such as batch normalization and dropout to improve the generalization accuracy of our models, and observe that deep CNN with LSTM does a very good job. VAE is used in the network to analyze their impact in data augmentation when the available training data is limited.
