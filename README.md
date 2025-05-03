I previously created different programs where i showed my ability in using neural networks(FFNNs, RNNs and CNNs), however in this program i tried using a 
recurrent neural network to predict the apple stock price for the next day, this can be adjusted to predict the next few days in advance and in future projects i'll make one that
responds to information such as news and company announcements

Using the knowledge i have about parameters needed in the neural network i was able to direct the neural network to select parameters that helped it display better results, 
I used a Bayesian Hyperparameter Tuner to find the best parameters, i also used this program to create(Feature Engineer) some new features that should help the model learn better

I also followed the recommended procedure of preprocessing data which requires splitting my data to a testing and training set before scaling and then further 
processing

In the hyperparameter tuning python file i'll advise that in the 5th cell, inside my BayesSearchCV function the **n_iter** variable should be changed from 1 to 30 for better results, it should be noted that this can slow down your system, make it overheat or have effects on your system that are similar to that which is being overworked
