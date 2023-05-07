Our main goal of this research is to investigate the correlation between sentiments of the tweets with its popularity.

For this project we have used two different datasets. One is labeled (0 and 1 for positive and negative sentiments respectively) dataset and the other one is unlabeled dataset. It is not possible to find a single dataset with labels and the features we needed for our investogation therefore we decided to take this approach. 

Main features we needed in a single dataframe to conduct this research were: tweet text, number of likes for that tweet, number of shares for that tweet and the sentiment score for that tweet so that we could compute the correlation. As we could not conduct the research using single dataset we followed the process mentioned below:

1. After performing all the required preprocessing of the data, we first trained a classifcation model on the labeled dataset.

2. Then we used that trained classification model to predict the labels for our unlabeled dataset along with sentiment score which in this case was computed using predict_proba function of the classifier model.

3. Then we computed the popularity score using the features: number of likes and number of shares.

4. Then computed linear and non-linear correlation between the populariy and the sentiment score. 

The steps are explained along with the code in more details.
