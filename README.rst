This project contains a basic example of a Neural Network.


- the .ipynb module must be used in a Jupyter notebook, the .py is a standard python (from command code python3 example_nn.py)

- data_example.csv is a fancy dataset to train and validate the model; only one feature numeric column and the target column. The target is sin * cos + random number. 

- the labels 'velocity' and 'force' are for illustrative purposes only, they could be anything

- data_example_test.csv is used to run the trained model; the target is sin * cos (without random numbers)

- the DNNRegressor does not consider a specific activation function for each layer (all the layer use the same activation function). This limitation can be removed in a more advanced example

Anybody who wants to use the network for some real use (or as a starting point), must answer some important questions:

- which is the 'correct' behaviour of the model? Even if you do not have a formula or a simple rule, what do you want it to do? (E.g.: tell if you are going too slow or too quick)

- why do you think that a Machine Learning program is better than a classica one? E.g. why you cannot use a mathematical formula?

- how many data do you have to train the network?

- is there any other feature that can be derived from the data and that could be important? E.g. difference between two consecutive values of the input features (that would be 'acceleration' if the feature is velocity)

In any specific case the tuning of the model's parameter must be done using real data, and implies some knowledge of the data themselves (e.g. for outliers, etc.)