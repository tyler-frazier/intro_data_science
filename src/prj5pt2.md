# Project 5 - Part 2

### Create a new markdown file and upload it to your GitHub repository.  Provide a link to your newly created `project5.md` file from your main index (parts 1 & 2).  Populate your newly created markdown file with your answers to the following questions.  Each part of this lab is worth 10 points.  Upload your response no later than midnight on Sunday, April 25th.

- Download the anonymized dataset describing [city_persons.csv](https://raw.githubusercontent.com/tyler-frazier/intro_data_science/main/data/city_persons.csv) from a larger city in a West African county and import it into your PyCharm project workspace (right click and download from the above link or you can also find the data pinned to the slack channel).  This time we will only use the variable `wealthC` as your target. It is not necessary to set a seed.  

Import your libraries, functions and create the commands `DoKFold`, `GetData` and `CompareClasses` as we have previously done in class.  Import the data and then complete the following steps.
  
- Execute a K-nearest neighbors classification method on the data.  What model specification returned the most accurate results?  Did adding a distance weight help?

- Execute a logistic regression method on the data.  How did this model fair in terms of accuracy compared to K-nearest neighbors?

- Next execute a random forest model and produce the results.  See the number of estimators (trees) to 100, 500, 1000 and 5000 and determine which specification is most likely to return the best model.  Also test the minimum number of samples required to split an internal node with a range of values.  Also produce results for your four different estimator values by both  comparing both standardized and non-standardized (raw) results.

- Repeat the previous steps after recoding the wealth classes 2 and 3 into a single outcome.  Do any of your models improve?  Are you able to explain why your results have changed?  
  
- Which of the models produced the best results in predicting wealth of all persons throughout the large West African capital city being described?  Support your results with plots, graphs and descriptions of your code and its implementation.  You are welcome to incorporate snippets to illustrate an important step, but please do not paste verbose amounts of code within your project report.  Avoiding setting a seed essentially guarantees the authenticity of your results. You are welcome to provide a link in your references at the end of your (part 2) Project 5 report.