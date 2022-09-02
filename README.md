# TED-Talks-mini-search-engine

**Note**
This code, here in the form of a notebook, is the result of a practical work session during my first year of Master. The instructions for this work were given to us by our professor [Sebastien Ferré(IRISA)](http://people.irisa.fr/Sebastien.Ferre/). The code was written in duo by [Niklas Barth](https://www.linkedin.com/in/niklasbarth/) and me.

This basic search engine quickly returns a list of URLs of TED talks, whose subject tries to match as closely as possible what the user has typed in.

The performance of the results has been improved thanks to the stemming of words and the removal of stop words. The order of the results is defined according to the TF-IDF method. The search is made quite fast thanks to the calculation of an index of the collection, which allows us to avoid having to search on all the words of all the texts at each query.

We used our search engine on 2467 TED talks transcripts on all sorts of topics [provided by Raounak Banik](https://www.kaggle.com/datasets/rounakbanik/ted-talks) , but it could be used to search on other collections.
