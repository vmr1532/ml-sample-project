# ml-sample-project
Ml sample project just for evaluation of skills

SEEDING IN ML-When to Seed the Random Number Generator

There are times during a predictive modeling project when you should consider seeding the random number generator.
Let’s look at two cases:

    Data Preparation. Data preparation may use randomness, such as a shuffle of the data or selection of values. Data preparation must be consistent so that the data is always prepared in the same way during fitting, evaluation, and when making predictions with the final model.
    Data Splits. The splits of the data such as for a train/test split or k-fold cross-validation must be made consistently. This is to ensure that each algorithm is trained and evaluated in the same way on the same subsamples of data.

