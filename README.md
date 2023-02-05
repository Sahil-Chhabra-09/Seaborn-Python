# Seaborn-Python
We will apply various graphical techniques using Seaborn to analyze worldwide box office revenue.

<b>Task 1: Data Loading and Exploration</b>

In this task, you are introduced to the project and learning outcomes. 

Once you are familiarized with the Rhyme interface, we begin working in Jupyter Notebooks, a web-based interactive computational environment for creating notebook documents. 

Next, we will import essential libraries such as NumPy, pandas, Seaborn, and matplotlib. 

Lastly, load the data sets into memory using pandas and display the first few entries. The TMDB data set contains 7400 movies and a variety of metadata.

<b>Task 2: Visualizing the Target Distribution</b>

The TMDB Box Office Prediction database was initially released so that teams could treat it like a regression problem and predict the worldwide box office revenue of 4400 movies provided in the test file. 

We will use this feature rich database for data analysis and data visualization in this project. 

In the next project, we will use the same database for feature engineering and feature visualization.  

To proceed to feature analysis, we first need to visualize the target. Using Seaborn's distplot function, we will plot the distribution of movie revenues. To illustrate the skew, we will also plot the distribution of revenue on a logarithmic scale using np.log1p.

<b>Task 3: Comparing Film Revenue to Budget</b>

Just as we did in Task 2, we will create two subplots: one for the distribution of the budget; the other to plot the log budget against log revenue. 

Perform the log transformation to make the distributions more manageable. 

<b>Task 4: Do Official Homepages Impact Revenue?</b>

Use the data to demonstrate the effect of an official homepage on movie revenue. 

Create appropriate features to indicate the presence of official movie homepages. We can use Seaborn's catplot function to plot the revenues for movies with and without homepages using our newly created features.

<b>Task 5: Distribution of Languages across Films</b>

As Hollywood is known globally, we would expect the data to support our intuition that English movies generate the highest revenue. 

In this task, we will use box plots to test this hypothesis. We might be surprised that our intuitions about the world may not always align.

<b>Task 6: Common Words in Film Titles and Descriptions</b>

Identify trends across movie titles and descriptions and their effect on revenue. 

Generate word clouds for movie titles and descriptions. Word Cloud is a data visualization technique used for representing text data in which the size of each word indicates its frequency or importance. 

<b>Task 7: How do Film Descriptions Impact Revenue?</b>

To identify which words have the highest impact on revenue, we tokenize and vectorize movie titles and descriptions, fit a linear regression model to it, and use ELI5 to display the high impact words.
