# Lexical Normalisation of Tweets 
COMP90049 Knowledge Technologies, Semester 1 2019, Project 1

Two methods for approximate string matching were used in the python script.
* Levenshtein Distance
* N-gram (N=2) algorithm
## Getting Started
Python 2.7 or newer is required
### install Python Packages with Pip
```
$ pip install python-Levenshtein
$ pip install nltk
```
## Running The Program
### Data Preprocessing
Run global.py to return the levetnshtein distance and corresponding predicted result in the pre_global.txt
Run ngrams.py to return the 2-gram distance and corresponding predicted result in the pre_ngram.txt
### Data Analysis
Run evaluate.py to calculate precision and recall which will display in the screen.
