# nosql-challenge

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

For this assignment, several steps were completed to set up the database to proform the necessary analysis in the 2nd part of this assignment.

To begin I imported the data via mongoimport in terminal, then from there set up the database in the Jupyter notebook to bebe able to update and manulipate the database.

First, I updated the database by adding a new restaurant location with all details about the location. Next, I needed to add the BusinessTypeID to the new restaurant record I had just created. Then the data had to be downsized as the magazine is not interested in restaurants in Dover, so code was written to identify and then remove the records for restaurants located in Dover. Lastly a quick conversion was completed to conver the Latitude & Longitude to devimals and the RatingValue to integer.

The next part begins the exploratory analysis. From here the process was fairly straight forward to answer the following questions.

1) Which establishments have a hygiene score equal to 20?
2) Whtih establishments in London have a RatingVale greater than or equal to 4?
3) What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score nearest to the new restaurant add, "Penang Flavours"?
4) How many establishments in each Local Authority are have a hygiene score of 0 (sorted from highest to lowest)?

Each section of the written code is designed to provide the answers to those questions.

The code from the terminal and throughout the Jupyter notebook was written based on in class examples and my copy of Python for Data Analysis: Data Wrangling with pandas, NumPy, and Jupyter 3rd Editiion by Wes McKinney (https://wesmckinney.com/book/). Additionally, I used both the CodePal Code Reviewer (https://codepal.ai/code-reviewer) and CodePal Bug Decector (https://codepal.ai/bug-detector) to assist in troubleshooting my code.
