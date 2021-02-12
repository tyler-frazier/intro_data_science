# Project 1

### Create a new markdown file and upload it to your GitHub repository.  Provide a link to your newly created `project1.md` file from your main index.  Populate your newly created markdown file with your answers to the following questions.  Upload your response no later than midnight on Wednesday, February 17th.

- Describe what is a package?  Also, describe what is a library?  What are the two steps you need to execute in order to install a package and then make that library of functions accessible to your workspace and current python work session?  Provide examples of how you would execute these two steps using two of the packages we have used in class thus far. Be sure to include an alias in at least one of your two examples and explain why it is a good idea to do so.

- Describe what is a data frame? Identify a library of functions that is particularly useful for working with data frames.  In order to read a file in its remote location within the file system of your operating system, which command would you use?  Provide an example of how to read a file and import it into your work session in order to create a new data frame.  Also, describe why specifying an argument within a `read_()` function can be significant.  Does data that is saved as a file in a different type of format require a particular argument in order for a data frame to be successfully imported?  Also, provide an example that describes a data frame you created.  How do you determine how many rows and columns are in a data frame? Is there an alternate terminology for describing rows and columns?

- Import the `gapminder.tsv` data set and create a new data frame.  Interrogate and describe the `year` variable within the data frame you created.  Does this variable exhibit regular intervals?  If you were to add new outcomes to the raw data in order to update and make it more current, which years would you add to each subset of observations?  Stretch goal: can you identify how many new outcomes in total you would be adding to your data frame?

- Using the data frame you created by importing the `gapminder.tsv` data set, determine which country at what point in time had the lowest life expectancy.  Conduct a cursory level investigation as to why this was the case and provide a brief explanation in support of your explanation. 

- Using the data frame you created by importing the `gapminder.tsv` data set, multiply the variable `pop` by the variable `gdpPercap` and assign the results to a newly created variable.  Then subset and order from highest to lowest the results for Germany, France, Italy and Spain in 2007.  Create a table that illustrates your results (you are welcome to either create a table in markdown or plot/save in PyCharm and upload the image).  Stretch goal: which of the four European countries exhibited the most significant increase in total gross domestic product during the previous 5-year period (to 2007)?

- You have been introduced to four logical operators thus far: `&`, `==`, `|` and `^`.  Describe each one including its purpose and function. Provide an example of how each might be used in the context of programming.

- Describe the difference between `.loc` and `.iloc`.  Provide an example of how to extract a series of consecutive observations from a data frame.  Stretch goal: provide an example of how to extract all observations from a series of consecutive columns.

- Describe how an api works.  Provide an example of how to construct a request to a remote server in order to pull data, write it to a local file and then import it to your current work session.

- Describe the `apply()` function from the `pandas` library.  What is its purpose?  Using `apply)` to various class objects is an alternative (potentially preferable approach) to writing what other type of command? Why do you think `apply()` could be a preferred approach?

- Also describe an alternative approach to filtering the number of columns in a data frame.  Instead of using `.iloc`, what other approach might be used to select, filter and assign a subset number of variables to a new data frame?









