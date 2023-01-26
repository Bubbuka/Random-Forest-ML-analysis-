# Random-Forest-ML-analysis-
As a Demonstrative exercice I implement a data analysis and ML model on a Google analytics dataset of 300k+ entries.  
  
The analysis is aiming to explore relations between the users and their spending patterns to to figure out some insigth about their interactions.  
With the model I´m trying to predict wether a given user on a specific visist is going to convert or not.  
After cleaning and reformatting the data, performing some feature optimization aswell, I proceed to divide my training set.  
Due to the extreme imbalance present in the data I decided to utilize a RandomForest model applying a SMOTE optimization to oversample the data and I´m able to succesfully train the model.  
  
The results are as follows:  

Accuracy score: 0.998727411555103 /
Precision score: 0.9578544061302682 /
Recall score: 0.946969696969697 

  
In conclusion this analysis was a very interesting way to demonstrate my thinking process, while also developping a pretty useful model that would help any web page administrator to apply some very succesful changes or campaigns.  
One objective of this exercice was to stay under 50 lines of code, for the sake of simplicity, and curiously this was by far the hardest part, besides overcoming the imbalance present on the dataset, as I was tempted at every line to add some other graphs and extra relations, but I prefer to leave a more    in-deph and professional analysis for the next step in my career path.  
Thank you for reading, check this link to see the raw data used in this exercice: Link
