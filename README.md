# search-engine
It is capable of answering single-word search queries efficiently.
The user needs to give a seed page url as input. The seed page( A good seed page is the one with many links embedded in it) can be any valid url which is used by the program to crawl the web.
Given the seed page url, the program takes a couple of minutes (usually 15-20 min) depending upon the seed page, to fetch and preprocess(ranking) the data crawled.

On calculating all the results, user can make infinite number of single-word queries and the program displays the top results based on the search.
The very famous Page Rank algorithm has been used in the program. The results are sorted in decreasing order of their ranks computed with the ranks displayed alongside.

To clone the repository

$ git clone https://github.com/laxmanverma/search-engine.git

to run the script 

$ python search_engine.py
