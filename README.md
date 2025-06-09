# 📊 Reddit Bigram Analysis – r/relationships

## 🧠 Why did I make it?
This project was created as part of a data analysis exercise to explore real-world textual data using natural language processing (NLP). 
The subreddit r/relationships was chosen because it contains rich, emotionally driven narratives that are well-suited for extracting patterns and common themes in human interaction.

## 📚 What I learned
Through this project, I learned how to:

- Use Reddit’s API to collect and save real Reddit post data

- Clean, preprocess, and lemmatize large text datasets using spaCy

- Remove stopwords and semantically unimportant phrases from text

- Generate frequency-based visualizations (bar plots, word clouds)

- Extract and analyze bigrams (two-word phrases) from text

- Filter and compare language usage before and after data cleaning

- Categorize language into themes like emotions, actions, and communication

- Visually compare how different filtering steps affect language patterns

## 🛠️ What tech did I use?
- **Python** for all data processing and analysis

- **PRAW** (Python Reddit API Wrapper) to extract Reddit posts

- **pandas** for data manipulation

- **spaCy** for lemmatization and stopword filtering

- **NLTK** for additional NLP utilities (like stopword lists)

- **collections.Counter** for word frequency analysis

- **matplotlib** for data visualization

- **wordcloud** to generate word and bigram clouds

- **Jupyter Notebook** as the primary development environment

## 📦 Files & structure
- reddit_relationships_posts.csv – dataset of Reddit r/relationships posts (title + text)

- notebook.ipynb – main analysis notebook

- README.md – this file

## 🔍 Highlights
- Bigram filtering and thematic grouping

- Visual comparison of language before and after stopword & semantic filtering

- Custom visualization styles for reporting and presentation

