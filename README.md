Indexer

Cd into the project root folder and run the command: python main.py
Make sure the corpus DEV is put in the data/ folder.

Search

1. Cd into the project root folder and run the command: pip install Django
2. run the command: python manage.py runserver, then wait for the inverted index loaded message displayed in the shell
3. Open the browser and go to http://127.0.0.1:8000/
4. Enter the query in the search box and click the search button. The results will be shown in the search result page.
5. If you want to search again, just press the Enter button.
6. If you want to use boolean retrieval, please check the boolean box. Only support AND, so you don't need input the operator between two words.

References

https://www.geeksforgeeks.org/create-inverted-index-for-file-using-python/
https://medium.com/@fro_g/writing-a-simple-inverted-index-in-python-3c8bcb52169a#:~:text=What%20is%20an%20Inverted%20Index,the%20term%20in%20the%20document.
https://www.codespeedy.com/tf-idf-model-for-page-ranking-in-python/#:~:text=The%20tf%2Didf%20stands%20for,information%20retrieval%20and%20text%20mining.
https://towardsdatascience.com/create-a-simple-search-engine-using-python-412587619ff5
https://towardsdatascience.com/hits-algorithm-link-analysis-explanation-and-python-implementation-61f0762fd7cf
https://towardsdatascience.com/pagerank-3c568a7d2332
https://blog.devgenius.io/lets-build-a-search-engine-with-python-3f8dd3320210
Introduction to Information Retrieval
