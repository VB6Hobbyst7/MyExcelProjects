# MyExcelProjects
Projects that I have worked on during DS-120 (Intro to Data Science) course and during leisure time.



1: Concessions Problem: (RafaelBroseghiniConcessions.xlsx)

  Find the Calories-Solver tab. You will also need to enable the solver extension as described in the book. Modify the sheet so that it   has the following constraints and goals: We want to find the minimum priced meal with 2400 calories that includes at least one     
  beverage, at least one main meal item, and at least one desert item.

2: Iris Data Clustering: (TrainingSetIris.xlsx)

  Part I -- Building and Validating a Model

  Randomize the data
  Split the data into a training set and a test set.  Put your test set into its own tab.
  Now working with the training data move the column that shows the kind of each Iris somewhere out of the way.
  Using the same procedure we did for our small dataset, Figure out your clusters.
  Calculate the distance from each sample to three different centroids - these will be 4-D
  Find the minimum distance (closest centroid) for each row
  Sum the minimum distances
  Create a column using match to indicate which cluster each row belongs to (1, 2, or 3)
  Setup and run solver
  Once solver has found a solution move back the column that contains the kind of each iris.  If you look at the names along side the     numbers you created in step 4 above it should be pretty clear which irises correspond to each number.
  Devise a way to calculate how often you correctly categorized the rows of your training set.  That is, if your spreadsheet says that a    row corresponds to a setosa and it does you get a point.  If the row was incorrectly categorized you don't get a point for that row.    You can use the IF function to look at the known value for this row and classify it as 1, 2, or 3 depending on what your solver has     led you to believe correspond to each variety.  Your training set has 120 rows so the number right out of 120 tells you how well you   
  are doing.
Part II -- Testing the Model on the test set.

  In this part of the assignment you will use the three centroids you calculated in Part I to classify the samples in the test set.

  This basically repeats what you did in Part I but you don't use Solver to figure out the centroids, you just USE the centroids you        calculated in Part I to classify each point.
  Copy and Paste the centroid information from your training tab to somewhere on your tab containing the test data.  
  Calculate the distance from each sample to three different centroids - these will be 4-D
  Find the minimum distance (closest centroid) for each row
  Sum the minimum distances
  Create a column using match to indicate which cluster each row belongs to (1, 2, or 3)
  Once again figure out how often you were correct.  How does your success rate for the test set compare to what you were able to do on   your training set?
  
3: Concessions - maximize Profit: (RafaelConcessions.xlsx)
Optimize the Concession stand **profits** using the following constraints:

The total number of items sold must be 200 or less
You cannot sell more than 25 hamburgers
You only have 30 Popsicles and 30 ice cream sandwiches
You can sell a maximum of 20 pizza
The combination of water, beer and soda must be more than the total of hamburgers pizza and hot dogs

4: Take the following sentence and paste it into a new excel spreadsheet (Tweet.xlsx)

Mr. Comey, who made the request on Saturday after Mr. Trump leveled his allegation on Twitter, has been working to get the Justice Department to knock down the claim because it falsely insinuates that the F.B.I. broke the law, the officials said.

Convert all of the characters to lower case
remove all of the punctuation marks
Copy the results of the cleaning 42 times and use the procedure we followed in class (also in chapter 3) to isolate each word from the sentence into its own cell, add a cell right next to it to show the length.
Bonus:   Now use a Pivot table to make a summary that shows each word along with the number of times it appeared in the sentence.

5: Building the Sentiment Analysis Model: (Airline Sentiment Broseghini.xlsx)
The goal for this assignment is to create two tables:  one summarizing the word counts from all the positive tweets in your training set, and a second summarizing all the negative tweets from your training set.

Get the Airline Tweet data from Kaggle -- see link on katie
Get rid of everything except the two columns that contain the positive or negative classification and the tweets
Use the cleaning process we went through in class to clean up all of the tweets
Split the data into a trainging (80%) and test (20%) set.  Store each on their own tab
Now sort the training data by positive or negative  (get rid of any marked neutral)
Put the positive tweets into a tab called 'Positive'  throw away a few tweets if necessary to have a nice round number
Put the negative tweets into a tab called 'Negative' and throw away a few tweets if necessary to have a nice round number
Now Use the procedure you learned in class to separate all of the tweets into words, and then create a pivot table to show how many times each word appeared in all of the tweets.

6: Linear Regression - Cricket Data: (CricketsRegression.xlsx)
Find the slope and intercept of the cricket data.

7: LCMS Games Data Since 2011: (LCMS Games Data Since 2011.xlsx)
Fun leisure time project mining some data from the Luther College Men's Soccer team using Pivot Tables.

8: LCWS Games Data Since 2011: (LCWS Games Data Since 2011.xlsx)
Fun leisure time project mining some data from the Luther College Women's Soccer team using Pivot Tables.
