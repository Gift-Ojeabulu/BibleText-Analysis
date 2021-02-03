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
