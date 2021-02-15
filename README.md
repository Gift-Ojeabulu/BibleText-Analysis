[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-360/)   

![header](https://capsule-render.vercel.app/api?type=wave&color=gradient&height=300&section=header&text=Portfolio%20Project&fontSize=90)

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)                 



## Introduction

This Python Projects is created with Streamlit and hosted on Heroku check the site for demo <http://bibleapplication.herokuapp.com/>

## Get Started

- Download [Python 3](https://python.org/downloads)
- Pip install streamlit

## Usage

Streamlit is A python framework for buiding data apllication.













# streamlit-bible-app
I built a bible app with streamlit deployed on heroku that has features like part of speech bible text tag, counts of word and graphs of word count.

```python
# A function to read our dataset-An Headstart
@st.cache
def load_bible(data):
    df = pd.read_csv(data)
    return df
    
    def main():
    stc.html(HTML_BANNER)
    menu = ["Home", "MultiVerse", "About"]

    df = load_bible("data/KJV_Bible.csv")
```

## 🚀 Quick Start

1. Install all the packages:
    ```bash
    pip install requirements.txt
    ```
2. Run the demo:
    ```bash
    streamlit run app.py
    ```
3. View the Streamlit app in your browser: `http://localhost:8501`
