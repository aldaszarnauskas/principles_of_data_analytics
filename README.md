## Table of contents
* [Introduction](#Intro)
* [Submission](#Submission)
* [Requirements](#Requirements)
* [Reference](#Reference)
* [License](#License)

## Intro
This repo contains one main file, task.ipynb as the submission for the Principles in Data Analytics module. I completed in total 10 tasks that are summarised in the [Submission](#Submission) section. In short, in this file you can see an analysis of the Iris dataset which contains data for 150 Iris samples from three different species[^1]. Each sample has info about 4 features: sepal length, sepal width, petal length, petal width. 


## Submissions
1. Source the Data Set 
Iris dataset from scikit-learn package was loaded

2. Explore the Data Structure
Various function were used to explore the Iris dataset and its metadata.

3. Summarize the Data
The summary statistics (mean, minimum, maximum, standard deviation, median) for the Iris dataset was calculated.

4. Visualize Features
The histogram for each feature of the dataset (sepal length, sepal width, petal length, petal width) was plotted.

5. Investigate Relationships
A scatter plot of two features, petal length vs petal width, was plotted. The data points were color coded based on species.

6. Analyze Relationship
The task 5 was continued here further and a regression line was plotted through the data points.

7. Analyze Class Distributions
A box-plots of the petal lengths for each of the three classes were plotted.

8. Compute Correlations
A correlation matrix between all four features were plotted.

9. Fit a Simple Linear Regression
An $R^{2}$ was calculated for the previous analysis.

10. Too Many Features
Here a pairplot from seaborn[^2] package was calculated.

## Requirements
Find the requirements for this project in [requirements.txt](requirements.txt).


## Reference
[^1]: https://scikit-learn.org/1.4/auto_examples/datasets/plot_iris_dataset.html
[^2]: https://seaborn.pydata.org/


## License
No license
