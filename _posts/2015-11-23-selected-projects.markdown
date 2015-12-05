---
layout: post
title:  "Additional Selected Projects"
date:   2015-11-23 16:54:37 -0500
categories: the_iron_yard
---


<p>
Below are 5 more of the <a href="https://github.com/tiyd-python-2015-08/assigments/tree/fee-collab" >28 projects</a> that I worked on as part of my Python Engineering class at The Iron Yard, Durham. Each title links to the associated GitHub repository.
</p>


<br>


## Data Science

---

### [American Time Use Survey Analysis][atus-gh]

**IPython Notebook containing analysis of the [American Time Use Survey data][atus-data].**  

This assignment was largely unguided, with the aim of exploring an unknown data source for ourselves. Getting my initial bearings was a challenge, as there were many files and a huge number of data points (not to mention the coded field names!). I focused on normal activities to ensure the data set was large enough to have relevance.  

**Project Details**  
**Time:** 3.5 days  
**Python Tools:** pandas, NumPy, Matplotlib, IPython Notebook, datetime  
**IPython Notebook:** [ATUS ipynb][atus-ipynb]  


<br>


### [Programming Language Classifier][pl-classifier-gh]  

**IPython Notebook loading and executing custom featurizers.**  

The challenge of this assignment was two-fold: (1) collect and access a corpus of snippets of programming languages and (2) use Scikit-Learn tools to classify the test snippets as accurately as possible. I manually built extensive featurizers and accompanying tests to be used with the `DecisionTreeClassifier` because the Naive Bayes classifier gave poor results for my data set.


**Project Details**  
**Time:** 3.5 days  
**Python Tools:** sklearn, nose, Matplotlib, IPython Notebook  
**IPython Notebook:** [Programming Language Classifier ipynb][pl-classifier-ipynb]

<br>


### [Road Rage][road-rage-gh]

**IPython Notebook presenting traffic simulation.**  

The goal of this assignment was to use a Monte Carlo simulation to determine the ideal speed limit for a 1&nbsp;km stretch of road. I put a lot of effort into a version of hard mode that, although working, needed just a bit more troubleshooting.

**Project Details**  
**Time:** 3.5 days  
**Python Tools:** random, math, NumPy, Matplotlib, IPython Notebook  
**IPython Notebook:** [Road Rage ipynb][road-rage-ipynb]

<br>


## Pure Python

---

### [What to Watch][what-to-watch-gh]  

**Command-line program to provide meaningful access to data in the MovieLens 100k database.**  

The purpose of this project was to make effective use of classes, list comprehensions, the `csv` module to read in data. I built a Django app later in the class that has similar functionality for the MovieLens 1M data set.  

**Project Details**  
**Time:** 3.5 days  
**Python Tools:** csv, math, os, sys  


<br>


### [Mystery Word / Evil Mystery Word][mystery-word-gh]  

**Command-line "hangman"-style game.**  

This was the very first weekend project and was a lot of fun to put together. I was able to finish the normal mode on Saturday afternoon, so was able to fully tackle the "Evil" version of the game—just try to beat it!

**Project Details**  
**Time:** 3.5 days  
**Python Tools:** deepcopy, os, random, unittest



[mystery-word-gh]:  https://github.com/ahartz1/mystery-word
[atus-gh]:          https://github.com/ahartz1/atus-analysis
[atus-data]:        http://www.bls.gov/tus/home.htm#data
[atus-ipynb]:        https://github.com/ahartz1/atus-analysis/blob/master/atus-analysis.ipynb
[road-rage-gh]:     https://github.com/ahartz1/road-rage
[road-rage-ipynb]:   https://github.com/ahartz1/road-rage/blob/master/road-rage.ipynb
[pl-classifier-gh]:  https://github.com/ahartz1/programming-language-classifier
[pl-classifier-ipynb]: https://github.com/ahartz1/programming-language-classifier/blob/master/programming-language-classifier.ipynb
[what-to-watch-gh]: https://github.com/ahartz1/what-to-watch
