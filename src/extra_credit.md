# DATA 146: Introduction to Data Science
## Extra Credit Report - due ...

### Analyze demographic data that describes Liberia

For this extra credit assignment, you are asked to analyze a portions of a household survey that describes the demographic composition of the West African country Liberia.  A household survey is a random, clustered and stratified sample from the larger population.  In order to successfully obtain the extra credit, you will need to complete the following steps.

- Join the slack channel [DATA146 Extra Credit](https://wmdsi.slack.com/archives/C01CMJ0LGQJ) and proceed to download the pinned file `lbr_persons.csv`.  If you have any difficulties accessing the team slack chat or downloading the `.csv` file please e-mail me at <tjfrazier@wm.edu> or preferably send me a direct slack message at [Tyler Frazier](https://wmdsi.slack.com/archives/DFBP51L9H)
- After you have downloaded the `.csv` file, `import pandas` and then also use the `pd.read_csv()` command to import the `.csv` file as a new `data.frame` into your **python** workspace.
- For starters assign `education` to a new `data.frame` as your `y` label.  Follow that by assigning all of the remaining features, also as a data.frame, to `x`.
- Use `train_test_split()` from `sklearn.model_selection` to create your training and testing datasets for both your features and labels.  Train a logistic regression model by specifying `logistic_regression.fit()` with your features and labels.  Use `logistic_regression.predict()` with your test features to estimate the accuracy of your trained logistic regression model.  Are you able to use `metrics.accuracy_score()` to produce the probability (in percent) of predicting the correct outcome with your model?
- Try scaling and/or normalizing the data to determine if doing so will improves your model's predictive power. Import the needed methods from `sklearn.preprocessing` and use with the `fit_transform()` and `transform()` commands.  For example you may want to start with 

```
xtrain = minmax.fit_transform(x_train)
xtest = minmax.transform(x_test)
```

- Also try `RobustScaler()`, `StandardScaler()` and `Normalizer()`.  Did any of these scaled transformations improve your model's predictive power when applied to the data before `.fit()` and then `.predict()`.
- Next specify and train a kNN model.  How does kNN perform in comparison to your best logistic regression?
- How about a decision tree or a random forest model?  Are you able to outperform the logistic regression with either machine learning method?

For your extra-credit deliverable, write a 2 to 3 page report that describes your investigation into the demographic composition of Liberia. Introduce your report by describing the data itself in terms of its size and shape. Produce histograms, pairwise correlation and probability density function plots of the data in order to further describe it. Provide estimates of accuracy from each of the four or five implementations as part of the report on your investigation into the data. Instead of using the `education` column from the `data.frame` as your label, you are also welcome to try using the `wealth` column.  Publish your extra credit report on GitHub as a webpage and share your link to the slack channel above.  Please feel free to ask questions on the slack channel and I will be happy to provide further direction or advice as needed.  Your extra credit report is due ...








