# KPMG-Task

This was originally done in Kaggle before imported into Github

The task was to take the customer data of a bicycle service company and determine was section of their new/ prospective clients that the marketing team would target in their latest campaign to ensure that they maximised the campaign and attracted high value customers.

I had to decide what characterised a high value customer and decided to go with the Average spend value of the customer. 
With this parameter, i then decided on a threshold value above which a customer would be considered a high value customer.

I then trained a random Forest Classifier from Scikit Learn Package to identify the high value customers based on other demographic information given.

I have Models.rar file that contains Two pickle files for the 2 Random Forest Classifier Models that were trained.
The first is the Model trained using Mean Spend as the deciding or target feature
The second is the Model trained using the Online order habit of the customer as the target feature

The code for both models is also displayed in the appropriately named notebooks
