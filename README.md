###### CS 345 - Project Proposal
1 **.** **Team:**
i. Camden Thomas
ii. James Richardson
2 **.** **Topic:**
i. The topic we’d like to approach is a multi-label classification problem for movie
genres; using keywords as features to predict what labels to apply. Moviegoers
can make quick decisions on whether they want to go see a particular movie just
from hearing “superhero movie” or “musical” as a descriptor. Correct
classification is more important than ever when using streaming services and
reviewing selections based on these keywords. The goal of this model is to better
classify movies into their respective genres, and be able to apply that to new
media just based on its keywords.
**ii.** **Describe the data used:**
TMDB 5000 Movie Dataset from Kaggle contains 20 categories of
characteristics, such as keywords, genres, runtime, and cast/crew for
nearly 5000 movies. Many of the columns could be used as a list of
features, and most will provide more than 30 features. This provides
freedom to analyze which category performs best at classifying movie
genres. The Category keywords appear to be the most closely related
and have the highest number of unique values. This will be a more than
adequate subset to train a model to use keywords (or a different category)
to predict what a movie genre is.
**iii.** **Describe the machine learning approaches used:**

1. Grid check
2. Validation spilt
3. Labeled data
4. Matplotlib for data visualization
5. Use of either Regression or SVM to better define data**iv.** **Include references or URLs to data origins:**

1. [Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata/data?select=tmdb_5000_movies.csv)**v.** **Explain what makes the data interesting and challenging:**

1. Genres can make or break a movie. The most challenging aspect of thisdataset is keyword consistency. A movie might have a keyword like “civil
war” and could return genres like superhero movies (“Captain America:
Civil War”) or westerns (Wild Wild West). We’ll have to be careful on how
we tweak things and look at data points independently.
3 **.** **Provide clear steps for the projects:**
i. Submitting the proposal
ii. Outlining the necessary coding components

1. Need a way to review CSV files
2. Need a way to parse keywords in a CSV file (remove junk data like “id:”so we just have the keywords by extracting “name:”

1. Convert keywords into numerical features
<||WXb23TXrUn3Rxz00yNNr89HV||>a. The movie has “space”, “ship”, and “alien”.
b. [1, 0, 1, 0, 0, 1]

1. Train the modela. Weigh the pros and cons of using regression vs SVM, then
implement one
b. Loop through training and testing with minor tweaks to find the
best approach

1. Write code to demonstrate the capabilities of the model
2. Write descriptions about the model/demonstrations to make it obviouswhat is happening and why we used that approach
4 **.** **Timeline for achieving project steps:**
i. Filter/Reshape/visualize Data: Latest end of the first week of April.
ii. Reduce features, split data, determine best classifier approach: Latest end of the
second week of April.
iii. Finalize and tweak the model to optimize accuracy: Latest end of the third week
of April.
iv. Write a report to demonstrate the model: Latest end of the last week of April.
v. Edit and polish the report: continue until deadline (May 4-8).
5 **.** **Breakdown of team responsibilities**
i. Shared: review dataset
ii. Shared: define tasks
iii. Shared: outline structure
iv. James: first half of the data for reviewing the CSV file. Manual review of data.
v. Camden: second half of data for reviewing CSV file. Manual review of data.
vi. Shared: discuss findings, choose classifier type
vii. Shared: break the full task into many sub-functions.
viii. Shared: paralleling tasks to ensure consistent work from both members
ix. James: Write half of the report
x. Camden: Write half of the report
xi. Shared: edit report

<||WXb23TXrUn3Rxz00yNNr89HV||>