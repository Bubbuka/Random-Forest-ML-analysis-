# Random-Forest-ML-analysis-
As a Demonstrative exercice I implement a data analysis and ML model on a Google analytics dataset of 300k+ entries./n
The analysis is aiming to explore relations between the users and their spending patterns to to figure out some insigth about their interactions.
With the model I´m trying to predict wether a given user on a specific visist is going to convert or not. 
After cleaning and reformatting the data, performing some feature optimization aswell, I proceed to divide my training set. 
Due to the extreme imbalance present in the data I decided to utilize a RandomForest model applying a SMOTE optimization to oversample the data and I´m able to succesfully train the model.
The results are as follows: 
Accuracy score: 0.974498348996698
Precision score: 0.5128755364806867
Recall score: 0.908745247148289
As we can see we have a optimal Accuracy score nearing 100%, but this is to be expected with such an imbalance present in the data. The precision score is not very impressive sitting at about 50%, but, due to the nature of the exercice, I´m not very concerned about a high False Positive rate as the costs per True Positive are negigeable. The score I´m really interested in is the Recall score, as this mesures the ammount of False Negatives predicted, and given I want to reduce this number as much as I can, so to not lose any potential buyers, and as we can see we manage this with a very respectable 90% score.
In conclusion this analysis was a very interesting way to demonstrate my thinking process, while also developping a pretty useful model that would help any web page administrator to apply some very succesful changes or campaigns.
One objective of this exercice was to stay under 50 lines of code, for the sake of simplicity, and curiously this was by far the hardest part, besides overcoming the imbalance present on the dataset, as I was tempted at every line to add some other graphs and extra relations, but I prefer to leave a more    in-deph and professional analysis for the next step in my career path.
Thank you for reading, check this link to see the raw data used in this exercice: Link
