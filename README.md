
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/gift-ojeabulu/streamlit-bible-app/main/app.py)


![header](https://capsule-render.vercel.app/api?type=wave&color=gradient&height=300&section=header&text=Bible-Text%20Analysis&fontSize=90)

## ✅ Goal
To build a bible app with that has features like part of speech bible text tag,Keywords, counts of word and graphs of word count.A useful Application of Machine Learning to the Religious Organization Industry



## ✅ MOTIVATION
I was in church with the traditional Bible and a thought went through my mind  and the thought was since it's said that Machine learning can be applied everywhere. 

Is it true ?

If yes ,how can I apply Machine learning to the bible. 

Then it strucked my mind, my other thought was like Natural language processing should be able to come in since - text analytics to be pricise,that was how the inspiration came. 

Then I move to the bible app on my phone scrolling through and I'm like since my aim is to integrate software development with machine learning 

Is there a way I can use machine learning to answer this questions?

* Detecting the Part of Speech for each word in the bible, Then if I can detect with nlp ,I should be able to plot with Python visualisation tool like seaborn, matplotlib.

* Getting the Keyword of each verses automatically without reading ,this can give a concise summary of what each chapter is about without reading.

* Can I search for topical words in the bible ?

To just get verses and chapters to prepare a message right there instead of going to Google.

E.g Verses associated with Faith, Grace , Giving and so on. 

This can help prepare sermon faster without doing much research maybe as a pastor or preacher . 

In the Future, Further improvement can be done by creating this as a Mobile App and adding more features.

We can even publish to Playstore for downloads because this hasn't been seen or done in any bible Application. 





## ✅  Demo video 1
![](https://github.com/Gift-Ojeabulu/BibleText-Analysis/blob/main/1st_Bibleapp.gif)


## ✅  Demo video 2
![](https://github.com/Gift-Ojeabulu/BibleText-Analysis/blob/main/app%20%C2%B7%20Streamlit12.gif)

## DEPLOYMENT 🚀

#### This website is deployed at [Heroku](https://www.heroku.com/)
#### You can access it [LIVE WEB APP ON HEROKU](https://bibleapp-analysis.herokuapp.com/)
#### Note: The website may take a minute to load sometimes, as the server may be in hibernate state


## ✅ Other Links
* [FEATURED PROJECT ON STREAMLIT WEEKLY DISCUSSION](https://www.linkedin.com/posts/gift-ojabu_streamlit-nlp-machinelearningsolutions-activity-6769922510034083840-zHUL) 
* [PROJECT ON LINKEDIN](https://www.linkedin.com/posts/gift-ojabu_webappdevelopment-pythonprogramming-streamlit-activity-6764841612100046849-0Ok3)

  







## Introduction

This Python Projects is created with Streamlit and hosted on Heroku 
## Get Started

- Download [Python 3](https://python.org/downloads)
- Pip install streamlit

## Usage

Streamlit is A python framework for buiding data apllication.









## 🚀 Quick Start

1. Install all the packages:
    ```bash
    pip install requirements.txt
    ```python
    # A function to load our dataset-An Headstart
   @st.cache
   def load_bible(data):
      df = pd.read_csv(data)
    return df
    
    def main():
    stc.html(HTML_BANNER)
    menu = ["Home", "MultiVerse", "About"]

    df = load_bible("data/KJV_Bible.csv")
      ```    
2.  Run the demo:
    ```bash
    streamlit run app.py
    ```
3.  View the Streamlit app in your browser: `http://localhost:8501`









## ✅ Tech stack!
    * Python
    * Heroku
    * altair
    * textblob
    * pandas
    * matplotlib
    * streamlit
    * neattext
    * spacy
    
   
    

## ✅  Built with
    
<code><img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" title="python"></code>
<code><img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/heroku/heroku-original.svg" title="heroku"></code>
<code><img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" title="git"></code>
<code><img height="30" src="https://raw.githubusercontent.com/numpy/numpy/7e7f4adab814b223f7f917369a72757cd28b10cb/branding/icons/numpylogo.svg"></code>
<code><img height="30" src="https://raw.githubusercontent.com/pandas-dev/pandas/761bceb77d44aa63b71dda43ca46e8fd4b9d7422/web/pandas/static/img/pandas.svg"></code>
<code><img height="30" src="https://matplotlib.org/_static/logo2.svg"></code>
<code><img height="30" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/1280px-Scikit_learn_logo_small.svg.png"></code>



## ✅ Features
1. Single Verse Search -
2. Multiverse Verse Search - Multiple Bible Verses at a time
3. Random Verse of the day
4. Term/Topic in the bible
5. Part Of Speech tag- Detect whether it is a Noun, Verb, Adjective, etc
indicated with different color, Where color Green is a Noun, Blue is a verb, etc
6. Main keyword in bible verse
7. Part Of Speech Tag Plot - Plots for the Part of Speech(Histogram).
8. Word Frequency Plot- Number of words in that verse(Histogram).
