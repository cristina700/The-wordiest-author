# The-wordiest-author
Analyzing how many words authors write per book and in their production

I have a database of a few popular authors and their books, with word counts for each book. So I want to know the authors who wrote more than 1 million words in their whole production, in order to do that I use the SUM command, GROUP BY author and HAVING Total-words >1000000. 
Then I want to know the authors who write in average more than 150,000 words per book. To do this I apply the functions AVG, GROUP BY and HAVING.
