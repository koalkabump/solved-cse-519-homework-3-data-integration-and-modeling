Download Link: https://assignmentchef.com/product/solved-cse-519-homework-3-data-integration-and-modeling
<br>
This homework will investigate data integration and model building in Python. Our goal is to go deeper by working with a data set where we have a very concrete idea of what we are working with.




This homework is based on the <a href="https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview">Ame</a>​ <a href="https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview">s</a> <a href="https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview">Housing</a> <a href="https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview">Dataset</a> on Kaggle, revolving around predicting the price that a particular real estate property (usually a home) will sell for. This is a continuously ongoing competition intended for beginners to become acquainted with data science. Since the dataset is relatively small and every field is descriptive, we will be focused on analyzing the data itself.




<h1>Data downloading</h1>

First of all, you need to join the challenge and download the data <a href="https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data">her</a>​ <a href="https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data">e</a>.​ The description of the data can also be found at this page.




<h1>Tasks</h1>




<ol>

 <li>Select a set of 10-15 of the most interesting variables. Do a pairwise Pearson correlation analysis on all pairs of these variables. Show the result with heat map and find out most positive and negative correlations. You can use the seaborn library to plot the heatmap, with instructions found <a href="https://seaborn.pydata.org/generated/seaborn.heatmap.html">her</a>​ <a href="https://seaborn.pydata.org/generated/seaborn.heatmap.html">e</a>.​</li>

 <li>Produce five other informative plots revealing aspects of this data. For each plot, write a paragraph in your notebook describing what interesting properties your visualization reveals. These must include:

  <ul>

   <li>at least one line chart</li>

   <li>at least one scatter plot or data map</li>

   <li>at least one histogram or bar chart</li>

  </ul></li>

 <li>Build a handcrafted scoring function to rank houses by “desirability”, presumably a notion related to cost or value. Identify what the ten most desirable and least desirable houses in the Kaggle data set are, and write a description of which variables your function used and how well you think it worked.</li>

 <li>Define a house “pairwise distance function”, which measures the similarity of two properties. Like a distance metric, similar pairs of very similar properties should be distance near zero, with distance increasing as the properties grow more dissimilar. Experiment with your distance function, and write a discussion evaluating how well you think it worked. When did it do well and when badly?</li>

 <li>Using your distance function and an appropriate clustering algorithm, cluster the houses using your distance function into 5 to 20 classes, as you see best. Present a visualization illustrating the clusters your method produced. How well do your clusters reflect neighborhood boundaries? (do not use neighborhood in your distance function) Write a discussion/analysis of what your clusters seem to be capturing, and how well they work.</li>

 <li>Set up a simple linear regression model on one or more variables to predict the pricing as a function of other variables. How well/badly does it work? Which variable is the most important one?</li>

 <li>Identify at least one external data set which you can integrate into your price prediction analysis to make it better. Write a discussion/analysis on whether this data helps with the prediction tasks.</li>

 <li>For ten different variables (some likely good, some likely meaningless) from the data set, build single-variable regression models, and for each one do a permutation test to determine a <em>p</em>​ ​-value of how good your predictions of the housing prices are. Use root-mean-squared error of the log(price) to score your model. In other words, compare how your model ranks by this metric on the real data compared to 100 (or more) random permutations of the housing priced assigned to the real data records.</li>

 <li>Finally, build the best prediction model you can to solve the task. Use any data, ideas, and approach that you like. Predict the pricing for instances at file “sample_submission.csv”. Report the score/rank you get.</li>

 <li><strong>Submit your results on Kaggle. </strong>Write​ the result into a csv file and submit it to the website. You should do this for every model you develop. Report​ the rank, score, number of entries, for your highest rank. Include a snapshot of your best score on the leaderboard as confirmation. Be sure to provide a link to your Kaggle profile.</li>

</ol>







<h1>Rules of the Game</h1>




<ol>

 <li>This assignment must be done <strong>individually by each student</strong>​ . It is not a group activity.​</li>

 <li>If you do not have much experience with Python and the associated tools, this homework will be a substantial amount of work. Get started on it as early as possible!</li>

 <li>All of your written responses will be put in the appropriate place in your notebook template. Get​ the template notebook form from Google Classroom!! You are allowed to add more cells, but definitely fill out the cells we give.</li>

 <li>We will discuss topics like linear regression in detail only after the HW is due. Muddle along for now, and we will understand the issues better when we discuss them in the course.</li>

 <li>To ensure that you are who you are when submitting your models, have your Kaggle profile show your face as well as a Stony Brook affiliation.</li>

 <li>There are some public discussions and demos relevant to this problem on Kaggle. It is okay for students to read these discussions, but they must write the code and analyze the data by themselves.</li>

 <li>You will submit your code so we can run it through MOSS to detect copying and plagiarism. Do your own work!!</li>

 <li>Our class Piazza account is an excellent place to discuss the assignment. Check it out at <a href="https://piazza.com/stonybrook/fall2018/cse519">com/stonybrook/fall2019/cse519</a><a href="https://piazza.com/stonybrook/fall2018/cse519">.</a><u>​</u></li>

</ol>




<strong> </strong>

<h1>Submission</h1>




Submit everything through Google classroom. As mentioned above, you will need to upload:

<ol>

 <li>The Jupyter notebook all your work is in (.ipynb file), derived from the provided template</li>

 <li>Python file (export the notebook as .py)</li>

 <li>PDF (export the notebook as a pdf file)</li>

</ol>




These files should be named with the following format, where the italicized parts should be replaced with the corresponding values:

<ol>

 <li>cse519_hw3_<em>lastname_firstname_sbuid</em>​ ​.ipynb</li>

 <li>cse519_hw3_<em>lastname_firstname_sbuid</em>​ ​.py</li>

 <li>cse519_hw3_<em>lastname_firstname_sbuid</em>​ ​.pdf</li>

</ol>


