# Fake News Detection

## Project Title
Fake News Detection using Logistic Regression

---

## Description
This project detects whether a news article is fake or real using Logistic Regression.  
It primarily uses the news title as input, along with optional numeric features like the number of tweets (`tweet_num`). Text data is converted to numerical features using TF-IDF vectorization.

---

## Dataset
 
- Columns:
  - `title` → headline of the news  
  - `news_url` → URL of the article  
  - `source_domain` → website domain  
  - `tweet_num` → number of tweets  
  - `real` → label (0 = fake, 1 = real)  
- Preprocessing:
  - Missing values in `source_domain` and `news_url` replaced with `"UNKNOWN"`
  - title is vectorised and tweet_num is scaled.
  

---

## Results
- Accuracy:83.8%  


---
