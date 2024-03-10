# Rock-vs-Mine-Prediction

Underwater Mine usage by the naval defense system provides great security but also possesses a threat to the
marine life and submarine vessels as the mines can be easily mistaken for rocks. We need a much more
accurate system to predict the object as it is very dangerous if a mistake is made. To have a great accuracy we
need accurate data to generate accurate results. We worked on the data set which is provided by Gorman, R. P.,
and Sejnowski, T. J. (1988). The data is used to train the machine.
This paper presents a method for the prediction of underwater mines and rocks using Sonar signals. Sonar
signals are used to record the various frequencies of underwater objects at 60 different angles. We constructed
three binary classifier models according to their accuracy. Then, prediction models are used to predict the mine
and rock categories. Python and Supervised Machine Learning Classification algorithms are used to construct
these prediction models.
4.1 ALGORITHM:
Step 1: We gather the dataset and perform data preparation and Exploratory Data Analysis to clean the dataset.
Step 2: We split the data into train and test datasets. Using them we evaluate the classification models.
Step 3: Following the evaluation, the top three performing models are determined to be KNN, SVM, and Logistic
regression.
Step 4: The accuracy of these models is evaluated, and a classification report is generated.
Step 5: We now fit the models to create a prediction system that's both accurate and efficient.
Step 6: Using the predictive systems, we can finally determine if the object is a Mine or a Rock.
