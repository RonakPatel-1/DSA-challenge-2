# DSA-challenge-2
**Problem Statement: **
Design an algorithm that recommends course videos in a more efficient manner than other algorithms, removing redundant or useless information from an information stream before presenting it to a user, or more specifically, as a subclass of an information filtering system that attempts to predict the "rating" or "preference" a user will give to an item.

Have attached the limited Data set into Domwonload folder which can be accessed/downloaded via link:
https://github.com/RonakPatel-1/DSA-challenge-2/tree/main/download

**Data set:**

There are two things training set folder which has the list of movie(s) id, ratings and year since the data set was very large almost not possible ot upload so have taken sample 12 files attached in above link.
Next file under download is the movie titles text file which has the list of movies.
https://github.com/RonakPatel-1/DSA-challenge-2/blob/main/download/movie_titles.txt

Based upon the limited data set just to do a poc have attached the code.

**Code:**

Here we will be using the Netflix DAta set and will be using two Data structure of Python as https://github.com/RonakPatel-1/DSA-challenge-2/blob/main/DSAchallenege2.ipynb in jupyter notebook with python latest versoin of 3.9.x

i am not gonna use panda since data is very large so there are chances to run out of memeory instead will use inbuilt DSA   dictioanry 


**Let us consider if fora movie is Avengers if i want recommendation then below:**

**step 1** : to calculate the average ratings and ratings count for a given movie Avengers  using the datastructure i have used which is dictionary.

**step 2** : Now let us calculate the other movies average ratings and counts which are there in out data set / training set

**step 3** : Now we will calculate cosine similarity between the two vectors

**Step 4** : In our case  for movie given name Avengers would be having an Vector A with average ratings and ratings count and Vector B will be for all other movies average ratings and their ratings count

**Step 5** :Now our next step would be the calculate the cosine similarity between these two movies and store them into a result.

**step 6** : After iterating through a loop of all movies present insude the data side it will show the top 10 list which matched as per the ratings
