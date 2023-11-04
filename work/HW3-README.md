# Analysing app patterns and creating insights on how to increase Google play app ratings.

The data is found on Kaggle, the dataset is about the google play store, and is formatted in CSV. The reason it cannot be easily retrieved using web scraping is the use of jQuery and other techniques that make it harder to retrieve. That is a stark difference from the itunes store, which has a more accessible web scarping. There is 13 Main variables that encompasses the many aspects of an application available on google play. The main variables are as follows:

App (Application name), Category (Category the app belongs to), Rating
(Overall user rating of the app (as when scraped)), Reviews (Number of user reviews for the app (as when scraped)), Size (Size of the app (as when scraped)), Installs (Number of user downloads/installs for the app (as when scraped)), Type (Paid or Free), Price (Price of the app (as when scraped)), Content Rating (Age group the app is targeted at - Children / Mature 21+ / Adult), Genres (An app can belong to multiple genres (apart from its main category). For eg, a musical family game will belong to Music, Game, Family genres.), Last Updated (Date when the app was last updated on Play Store (as when scraped)), Current Ver (Current version of the app available on Play Store (as when scraped)), Android Ver (Min required Android version (as when scraped))

The data provides the possibility of better understanding applications on google play. The trends of successful apps, and those of unsuccessful app. The analyzed results can be used to make more successful apps, and the variables that matter the most.

The way I accessed this dataset is by downloading the CSV from the kaggle website and using my local device to manipulate and analyze the data.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Exploratory Questions

The things you need before installing the software.

* Compare the distributions of Content Rating, Genres, Rating, and Reviews. What are the trends between those variables?
* Describe each App category with different rating, genres, and installs?
* Using ANOVA to see if Content Rating, Genres, Rating, and Reviews are dependent on another variable. Create regression models between the dependent variable and the independent variables.

TECH
* Seaborn/Matplotlib
* ANOVA/Regression

### Exploratory analysis method

Going to use NLP to find some similarities and insights from the reviews on the apps. Furthermore use group by and pivot_tables to create some outcomes. Will create a mosaic plot of paid and unpaid apps, conduct an x2 test and try to find interesting facts.

A step by step guide that will tell you how to get the development environment up and running.

```
$ First step
$ Another step
$ Final step
```

This homework is the first step in creating your final project.  Choose a question related to a topic you want to know more about.  This can be from your work, another course you are taking, your thesis research, or just a personal curiosity.  The question/project can involve classified or unclassified data, however, only do a classified project if you have access to work on it between class sessions.

1. Create a directory in your git repository called Project-Lastname
2. Create a README.md file in your project directory that includes:

 - Initial question
 - Intended type of analysis (e.g. inferential, mechanistic)
 - Describe initial analysis plan
 
3. Create a jupyter notebook with code of an initial exploration  (question-data symbiotic relationship)

4. Download the Jupyter Notebook and upload it to Blackboard and email to the instructor


#### Rubric:
| **Criteria**    | **Rating**     |  **Rating**     |  **Rating**     | **Points**  |
| -------------   |:-------------: | :-------------: | :-------------: |  -----: |
| Did the student create an initial question?  | 5 pts <br /> Excellent Completed task without additional assistance from instructor | 2.5 pts  <br /> Adequate Completed task but with additional assistance from instructor| 0 pts <br /> Missing Unsuccessfully completed task |5 pts |
| Did the student describe the intended type of analysis? | 5 pts <br /> Excellent Completed task without additional assistance from instructor | 2.5 pts <br /> Adequate Completed task but with additional assistance from instructor| 0 pts <br /> Missing Unsuccessfully completed task |5 pts |
| Did the student describe their initial analysis plan? | 5 pts <br /> Excellent Completed task without additional assistance from instructor | 2.5 pts <br /> Adequate Completed task but with additional assistance from instructor| 0 pts <br />  Missing Unsuccessfully completed task |5 pts |
| Did the student create code to conduct initial exploration?| 5 pts <br /> Excellent Completed task without additional assistance from instructor | 2.5 pts <br /> Adequate Completed task but with additional assistance from instructor| 0 pts <br />  Missing Unsuccessfully completed task |5 pts |
||||Total Score| 20 pts|


After completing the Lab and Homework, continue practicing editing your readme file and jupyter notebook.  This is how all homework will be submitted in the class.