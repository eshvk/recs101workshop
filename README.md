Building Recommendation Products 101 Hands on Session
=====================================================
Building Recommendations Products 101 Workshop for [Crunch Conf](http://crunchconf.com/#workshops)

To run
* Download and install the latest Anaconda (2.7) distribution from http://continuum.io/downloads
* `pip install annoy`
* `git clone https://github.com/eshwaran/recs101workshop.git`
* `cd ~/recs101workshop`
* `cd MovieData && tar -xvf grouplens.tar.bz2 && cd ..`

Load the notebook as follows:
* `ipython notebook notebooks/Recs101.ipynb`

Annoy
--------
[Annoy](https://github.com/spotify/annoy) is an open source library that we developed to allow us to do fast approximate nearest neighbor searches in high dimensional spaces. We have both C++, python, and Java versions of annoy. Annoy can be installed using pip.
* `sudo pip install annoy`

Slides
------

Available [here](http://www.slideshare.net/eshvk/recommendations-101)
