# 🧾 Project 34 – Analyzing Helpfulness in Amazon Fine Food Reviews

### 📖 Description
NLP project analyzing **review helpfulness**, **sentiment**, and **readability**  
using the [Amazon Fine Food Reviews dataset](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews).

The project investigates what makes an online review *helpful* by exploring  
linguistic and emotional features of user feedback.  
It applies various **Natural Language Processing (NLP)** techniques to  
analyze, visualize, and interpret text patterns that influence perceived helpfulness.

---

### 🧠 Objectives
- Identify linguistic and emotional characteristics of helpful reviews.  
- Compare subsets of reviews based on helpfulness ratios (L1, L2, L3).  
- Perform sentiment and readability analyses to find statistical patterns.  
- Summarize and interpret findings in clear English discussion.

---

### ⚙️ Methods and Tools
- **Python** (Pandas, NLTK, SpaCy, TextStat, Sumy, Scikit-learn)  
- **Text Analysis:** Tokenization, Sentiment Scoring (VADER), Readability Metrics  
- **Visualization:** Seaborn, Matplotlib  
- **Summarization:** TextRank (Sumy)  
- **Similarity:** TF-IDF + Cosine Similarity  
- **Statistical Analysis:** Correlation and comparative metrics

---

### 🧩 Project Structure
| Step | Task | Description |
|------|------|-------------|
| 1–3 | Data Preparation | Create subsets L1, L2, L3 by helpfulness ratio |
| 4 | Global Statistics | Token, character, and structure analysis |
| 5 | Sentiment Analysis | Sentiment polarity comparison |
| 6 | Readability Analysis | Flesch, Fog, SMOG, ARI metrics |
| 7 | Summarization & Similarity | Generate summaries and measure semantic overlap |
| 8 | Discussion & Conclusion | Final reflection on findings |

---

### 📊 Dataset
- **Source:** [Kaggle – Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)  
- **Provider:** SNAP / Stanford University  
- **Size:** ~500,000 reviews  
- **Fields:** ProductId, UserId, ProfileName, Score, Time, Summary, Text, HelpfulnessNumerator, HelpfulnessDenominator, etc.

---

### 🏁 Results Summary
- Helpful reviews are typically **longer, richer in detail, and emotionally positive**.  
- Readability and sentiment jointly influence how users perceive usefulness.  
- Summaries reveal stylistic differences across helpfulness levels.  
- Statistical findings confirm that **depth + positivity = higher helpfulness**.

---

### 🚀 Future Work
- Apply the same pipeline to other review domains (movies, hotels, etc.).  
- Extend sentiment models with transformer-based embeddings.  
- Explore causal relationships between linguistic cues and perceived trust.

---

### 🧑‍💻 Author
Project completed for **NLP Coursework 2025**  
by Tomoko Takami 
Instructor: *[Instructor Name]*  
Department of [Your Department or University Name]

---

> 📝 *This repository includes code, analysis results, and written discussion in English.  
> It demonstrates an end-to-end NLP pipeline for analyzing review helpfulness.*
