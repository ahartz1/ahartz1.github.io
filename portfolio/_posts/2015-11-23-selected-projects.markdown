---
layout: post
title:  "Selected Projects"
date:   2015-11-23 16:54:37 -0500
categories: The Iron Yard
---

<p>
Below are 6 of the <a href="https://github.com/tiyd-python-2015-08/assigments/tree/fee-collab" >28 projects</a> that I worked on as part of my Python Engineering class at The Iron Yard, Durham. Each title links to the associated GitHub repository. I have broken them out into the three overarching categories of (1) <a href="#django">Django</a>, (2) <a href="#data-science">Data Science</a>, and (3) <a href="#pure-python">Pure Python</a>.
</p>

<a name="django" />

## Django

---

### [Brew Keeper][brew-keeper-gh]

<div style="align: center; float: right; width: 220px; padding-left: 10px">
<img src="{{ site.baseurl }}/assets/brew-keeper-iphone.png" >
</div>

**Web app to _create_, _brew_, _refine_, _store notes on_, and _share_ coffee recipes. (Final Project)**  

Each student at The Iron Yard was required to pitch a final project idea, and I had been having difficulty coming up with one that was feasible. Although I came up with this project at 3:30&nbsp;a.m. on pitch day, I was very excited about the idea and was thrilled when we started working on it less than 12 hours later.  

**Project Details**  
**Time:** 20 days  
**Collaborators:** Shay Hall (FEE), David White (FEE), and Kathleen Rauh (Python)  
**Python Tools:** Django, Django REST API framework, PostgreSQL, Heroku, Travis-CI, DRF Nested Routers, Django CORS Headers, requests, nose, Mailgun  
**Full Site:** [www.brew-keeper.com](www.brew-keeper.com)  
**API Wiki:** [Development Notes][brew-keeer-dn]

<br>

### [URLy Bird][urly-bird-gh]

**Web app with URL-shortening functionality.**  

<img src="{{ site.baseurl }}/assets/urly-bird.png">

<br>

We worked very quickly and had "normal mode" covered by Saturday, giving us time to focus on polishing up the layout and bootstrap implementation.  

**Project Details**  
**Time:** 3.5 days  
**Collaborator:** Tyler Kotkin (Python)  
**Python Tools:** Django, PostgreSQL, Bootstrap 3, Heroku


<br>

<a name="data-science" />

## Data Science

---

### [American Time Use Survey Analysis][atus-gh]

**IPython Notebook containing analysis of the [American Time Use Survey data][atus-data]**  

This assignment was largely unguided, with the aim of exploring an unknown data source for ourselves. Getting my initial bearings was a challenge, as there were many files and a huge number of data points (not to mention the coded field names!). I focused on normal activities to ensure the data set was large enough to have relevance.  

**Project Details**  
**Time:** 3.5 days  
**Python Tools:** pandas, NumPy, Matplotlib, IPython Notebook, datetime  
**IPython Notebook:** [ATUS ipynb][atus-ipynb]  


<br>


### [Programming Language Classifier][pl-classifier-gh]  

**IPython Notebook loading and executing custom featurizers**  

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

<a name="pure-python" />

## Pure Python

---

### [Mystery Word / Evil Mystery Word][mystery-word-gh]  

**Command-line game**  

This first weekend project was a lot of fun to put together. I was able to finish the normal mode on Saturday afternoon, so was able to fully tackle the "Evil" version of the game—just try to beat it!

**Project Details**  
**Time:** 3.5 days  
**Python Tools:** deepcopy, os, random, unittest



[brew-keeper-gh]:   https://github.com/Brew-Keeper/brew-keeper-api
[brew-keeer-dn]:    https://github.com/Brew-Keeper/brew-keeper-api/wiki/Development-Notes
[urly-bird-gh]:     https://github.com/ahartz1/urly-bird
[mystery-word-gh]:  https://github.com/ahartz1/mystery-word
[atus-gh]:          https://github.com/ahartz1/atus-analysis
[atus-data]:        http://www.bls.gov/tus/home.htm#data
[atus-ipynb]:        https://github.com/ahartz1/atus-analysis/blob/master/atus-analysis.ipynb
[road-rage-gh]:     https://github.com/ahartz1/road-rage
[road-rage-ipynb]:   https://github.com/ahartz1/road-rage/blob/master/road-rage.ipynb
[pl-classifier-gh]:  https://github.com/ahartz1/programming-language-classifier
[pl-classifier-ipynb]: https://github.com/ahartz1/programming-language-classifier/blob/master/programming-language-classifier.ipynb
