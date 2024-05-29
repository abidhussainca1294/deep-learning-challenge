# Overview:

In this analysis a neural networks model is developed for nonprofit foundation Alphabet Soup,  using the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
A CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years is used for creating the model.

# Results:

*Data Preprocessing
    * Target variables: "IS_SUCCESSFUL" column which represent was the money used effectively (1) or not (0).
    * Feature variables: "APPLICATION_TYPE," "AFFILIATION," "CLASSIFICATION," "USE_CASE," "ORGANIZATION," "STATUS," "INCOME_AMT," "SPECIAL_CONSIDERATIONS," and "ASK_AMT" columns in the datset.
    * Removed variables: "EIN" and "NAME" - Identification columns are removed.

* Compiling, Training, and Evaluating the Model
    * Three models were developed for optimization of accuracy. The model that provides the best result has following characteristics:
        * Number of hidden layers : 3
        * 40,30,20 neurons are used in each hidden layers respectively.
        * "relu" activation function for each layer.
    * The model achieved an accuracy of 72.5% wit the test data which is less than the taget model performance of 75%.

* Summary:

The model achieved a highest accurracy of 72.5%. Keras sequential model is used. It is observed that even adding hidden layers doesnot brings a big change in accuracy. Change in number of neuron also didnt affect much on accuracy.
To acheive the target performance different neural network model and activation function should be used. Higher Corelation between input and output should be established for higher prediction accuracy.


