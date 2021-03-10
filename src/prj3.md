# Project 3

### Create a new markdown file and upload it to your GitHub repository.  Provide a link to your newly created `project3.md` file from your main index.  Populate your newly created markdown file with your answers to the following questions.  This lab is worth 10 points.  Upload your response no later than midnight on Tuesday, March 16th.

- Download the dataset [charleston_ask.csv](charleston_ask.csv) and import it into your PyCharm project workspace.  Specify and train a model the designates the asking price as your target variable and beds, baths and area (in square feet) as your features.  Train and test your target and features using a linear regression model.  Describe how your model performed.  What were the training and testing scores you produced?  How many folds did you assign when partitioning your training and testing data.  Interpret and assess your output.

- Now standardize your features (again beds, baths and area) prior to training and testing with a linear regression model (also again with asking price as your target).  Now how did your model perform?  What were the training and testing scores you produced?  How many folds did you assign when partitioning your training and testing data.  Interpret and assess your output.

- Then train your dataset with the asking price as your target using a ridge regression model.  Now how did your model perform?  What were the training and testing scores you produced?  Did you standardize the data?  Interpret and assess your output.

- Next, go back, train and test each of the three previous model types/specifications, but this time use the dataset charleston_act.csv (actual sale prices).  How did each of these three models perform after using the dataset that replaced asking price with the actual sale price?  What were the training and testing scores you produced?  Interpret and assess your output.

- Go back and also add the variables that indicate the zip code where each individual home is located within Charleston County, South Carolina.  Train and test each of the three previous model types/specifications.  How did each one fair?  Interpret and assess your output.

- Finally, consider the model that produced the best results.  Would you estimate this model as being overfit or underfit?  If you were working for a Zillow as their chief data scientist, what action would you recommend in order to improve the predictive power of the model that produced your best results?

