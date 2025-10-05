# PRODIGY_DS_04

## Task 4: Sentiment Analysis on Social Media Data

This task is part of my Prodigy Infotech internship.  
The objective was to **analyze and visualize sentiment patterns in social media data** to understand public opinion and attitudes towards specific topics or brands.

---

### Contents

- `task4.ipynb` → Jupyter notebook with code for analysis and visualization  
- `twitter_training.csv` → Dataset used for the task  
- Output plots → Bar charts and Word Clouds  

---

###  Approach

1. **Data Loading:**  
   - Imported `twitter_training.csv` into a pandas DataFrame.

2. **Data Preprocessing:**  
   - Dropped rows with missing tweet content or sentiment.  
   - Cleaned the tweet text (removed URLs, mentions, hashtags, converted to lowercase).  
   - Standardized sentiment labels to lowercase (`positive`, `neutral`, `negative`)

3. **Sentiment Analysis:**  
   - Visualized **sentiment distribution** using a bar chart.  
   - Generated **word clouds** for each sentiment category to show common words.
---

###  Visualizations

- **Sentiment Distribution Bar Chart:** Shows counts of positive, neutral, and negative posts.  
- **Word Clouds by Sentiment:** Highlights frequent words used in each sentiment category, providing insight into public opinion.

---

###  Tools & Libraries

- `pandas`, `numpy` → Data manipulation  
- `matplotlib`, `seaborn` → Visualization  
- `wordcloud` → Generate word clouds   

---

