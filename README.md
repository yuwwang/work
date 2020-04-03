<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-162712578-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-162712578-1');
</script>

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
Levenshtein.distance() is used to calculate Levenshtein distance between two strings.

nltk.bigrams() is used to break a string into 2-grams form.

## Running The Program
### Data Preprocessing
Run LD.py to return the levetnshtein distance and corresponding predicted results in the pre_global.txt

Run n_gram.py to return the 2-gram distance and corresponding predicted results in the pre_ngram.txt
### Data Evaluation
Run evaluate.py to calculate precision and recall and print the results in the screen.
