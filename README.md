# TED-Talks-mini-search-engine

**Notes**: *This code, here in the form of a notebook, is the result of a practical work session during my first year of Master. The instructions for this work were given to us by our professor [Sebastien Ferré(IRISA)](http://people.irisa.fr/Sebastien.Ferre/). The code was written in duo by [Niklas Barth](https://www.linkedin.com/in/niklasbarth/) and me.*

This basic search engine quickly returns a list of URLs of TED talks, where the text of the talks contains all the words the user has typed.

The performance of the results has been improved thanks to the stemming of words and the removal of stop words. The order of the results is defined according to the TF-IDF method. The search is made quite fast thanks to the calculation of an index of the collection, which allows us to avoid having to search on all the words of all the texts at each query.

We used our search engine on 2467 TED talks transcripts on all sorts of topics [provided by Raounak Banik](https://www.kaggle.com/datasets/rounakbanik/ted-talks) , but it could be used to search on other collections.

An example of a possible improvement (which I might do later) could be to make it so that when the user types a string of words in quotes, the search engine returns the URLs of the talks that contain these words directly afterwards, whereas at the moment the engine will simply return the URLs of the talks that contain these words but not necessarily directly afterwards, and even if they are put in quotes. 
