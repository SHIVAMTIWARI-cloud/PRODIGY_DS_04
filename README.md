# PRODIGY_DS_04
# PRODIGY_DS_04 — Sentiment Analysis & Visualization

This project is a part of **Prodigy Infotech’s Data Science Internship** — Task 4. The aim of this task is to analyze and visualize sentiment patterns in social media (Twitter) data to understand public opinions and attitudes toward specific topics or brands.

---

## 🧠 Objective

To perform **sentiment analysis** on social media posts using Natural Language Processing (NLP), and visually represent the data using graphs and word clouds. This project helps in identifying public sentiment (Positive, Negative, Neutral) about various topics mentioned in tweets.

---

## 🗂️ Dataset

- **Name**: `twitter_training.csv`
- **Source**: Provided by Prodigy Infotech [🔗 GitHub Dataset](https://github.com/Prodigy-Infotech/data-science-datasets/tree/main/Task%204)
- **Columns**:
  - `ID` – Unique identifier
  - `Topic` – Mentioned subject (e.g., brand, product, or theme)
  - `Sentiment` – Labelled sentiment (`Positive`, `Negative`, `Neutral`)
  - `Tweet` – Actual text content

---

## 🛠️ Tools & Libraries Used

- **Python**
- **Jupyter Notebook**
- **Libraries**:
  - `pandas`, `numpy` – Data manipulation
  - `nltk` – Text preprocessing (stopwords, lemmatization)
  - `re`, `string` – Regex and punctuation handling
  - `matplotlib`, `seaborn` – Data visualization
  - `wordcloud` – Word cloud generation

---

## 🔎 Key Steps Performed

1. **Data Loading & Inspection**
   - Loaded the CSV without headers and manually labeled columns.
   - Checked for missing/null values.

2. **Text Preprocessing**
   - Lowercased the text
   - Removed punctuation, special characters, and stopwords
   - Tokenized and lemmatized words using NLTK

3. **Sentiment Distribution**
   - Plotted countplot of sentiment classes (Positive, Negative, Neutral)

4. **WordCloud Visualization**
   - Generated WordClouds for each sentiment category
   - Helps identify most frequently used terms per sentiment type

5. **Bar Plot of Most Frequent Words**
   - For each sentiment, plotted top words using frequency counts

6. **Basic Insights**
   - Compared sentiment distribution across topics
   - Identified which topics had most negativity or positivity

---

## 📊 Screenshots & Results

📎 Screenshots of all major outputs and visualizations are included in this repository:
- Data distribution
- Preprocessing examples
- WordClouds
- Sentiment charts

---

## 📁 Files in This Repo

| File | Description |
|------|-------------|
| `Sentiment Analyze and Visualize .ipynb` | Main Jupyter notebook with code |
| `twitter_training.csv` | Dataset used for analysis |
| `Screenshots/*.png` | Visual results and charts |
| `README.md` | Project description and summary |

---

## 🙌 Acknowledgements

- **Prodigy Infotech** – Internship opportunity and dataset
- **NLTK**, **Pandas**, and open-source community for tools & libraries

---

## 🚀 Outcome

This project demonstrates how sentiment analysis can be applied to social media data to generate business insights and public sentiment trends. Visualization enhances interpretability for non-technical stakeholders.

---

## 📧 Contact

**Author**: Shivam Tiwari  
**Internship**: Data Science Intern, Prodigy Infotech  
