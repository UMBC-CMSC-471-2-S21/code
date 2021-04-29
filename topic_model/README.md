# topic-model-example

This repository contains notebooks adapted from the short tutorial *"Topic modelling with Scikit-learn"*, presented at [PyData Dublin](https://www.meetup.com/PyDataDublin/) in September 2017. 

### Contents

The summary tutorial is covered [in these slides](topic-modelling-with-scikitlearn.pdf).

There are two IPython notebooks:

1. [Preprocessing](Preprocessing.ipynb): Provides a basic introduction to preprocessing documents with *scitkit-learn*.
2. [NMF Topic Models](NMFtm.ipynb): Covers the application and interpretation of topic models via the NMF implementation provided by *scitkit-learn*.

To demonstrate the topic modeling techniques, a sample dataset [is provided here](data/articles.txt). This consists of 4,551 news articles from 2016, stored in a single text file (25MB), one article per line.

### Dependencies

This code has been tested with Python 3.8. The core package requirements are:

- *scikit-learn* (tested with v0.19.0)
- *numpy*
- *matplotlib*

### Links and References

- [*Scikit-learn* home](http://scikit-learn.org/stable/)
- [NMF documentation for *scikit-learn*](http://scikit-learn.org/stable/modules/generated/sklearn.decomposition.NMF.html)
- Lee, D. D., & Seung, H. S. (1999). Learning the parts of objects by non-negative matrix factorization. Nature. [[PDF]](http://www.columbia.edu/~jwp2128/Teaching/E4903/papers/nmf_nature.pdf)
- Blei, D. M. (2012). Probabilistic topic models. Communications of the ACM, 55(4). [[Link]](https://cacm.acm.org/magazines/2012/4/147361-probabilistic-topic-models/fulltext)
- O’Callaghan, D., Greene, D., Carthy, J., & Cunningham, P. (2015). An analysis of the coherence of descriptors in topic modeling. Expert Systems with Applications. [[PDF]](http://derekgreene.com/papers/ocallaghan15eswa.pdf)
