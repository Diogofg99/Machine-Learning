# Machine-Learning
Predictive model based on a dataset of 22400 observations to predict a binary tax rate.

This project comes as requested by the Newland Government, given the context of a newly established taxation system. As is common every year, hundreds of space voyagers, sent by the International Orbital Transportation Services, arrive at the many Newland arrival ports, filled with newcomers looking for better lives and opportunities.

It is important for the governmental agencies, for matters of policy, strategy and decision-making, to predict, given a specific set of information about the immigrants, whether an individual will be taxed at 15% of his income or 30%. This binary tax system considers whether a citizen earns an income above or below the societal average. 

This is particularly useful, as it may have implications regarding the following year’s governmental budget, and thus predicting how the coming individuals may contribute to the planet’s economy. Also, the predictions can be utilized as means of selecting which individuals can or cannot live
and work in Newland, for example, if the government needs higher-earning citizens.

Scientifically, the attempt was to apply a machine-learning algorithm, training it to a given dataset with 22.400 records and solve what can be seen as a “classification problem”- classifying individuals with 0 or 1 in which 0 represents an income below average and therefore a tax rate of 15%, and 1 represents an income above average and thus a tax rate of 30%. 

This model will then be applied to a different dataset with 10.100 records, predicting the classification for those individuals, of which this scientific group does not know the ground-truth, the true results are however known to the government, as a way to test the accuracy and precision of the model produced.

The model’s prediction quality will be evaluated through the F1-Score, which is a harmonic mean between out of the whole predicted positives, how many were correctly predicted and recall out of all actual positives, how many the model got right, that is, respectively, precision and recall.
