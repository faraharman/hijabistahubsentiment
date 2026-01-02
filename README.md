# Hijabistahub TikTok Sentiment Analysis 📊✨

## 📌 Project Overview
Hijabistahub is a Malaysian modest fashion brand that actively promotes its products on TikTok.  
This project analyzes **audience sentiment and engagement trends** across Hijabistahub-related TikTok content using **AI-powered sentiment analysis and predictive modelling**.

The goal is to help the brand better understand public perception, improve marketing strategies, and align content with customer expectations.

---

## 🎯 Objectives
- Collect and preprocess TikTok video and comment data
- Perform sentiment labelling on user comments
- Analyze engagement metrics and sentiment trends
- Build and evaluate predictive models for sentiment classification
- Provide actionable business insights for marketing decisions

---

## 📂 Data Collection
Data was collected using the **Apify platform**, utilizing:
- **TikTok Data Extractor** – video metadata (views, likes, shares, comments, etc.)
- **TikTok Comment Scraper** – user comments

📌 Scope:
- 20 popular videos from Hijabistahub’s official TikTok account  
- Maximum 50 comments per video  
- 447 qualitative rows (comments)  
- 892 quantitative rows (engagement metrics)

---

## 🧹 Data Preprocessing
Data preprocessing included:
- Removing duplicates and irrelevant records
- Cleaning text (emojis, slang, mixed language)
- Structuring data for analysis and modelling

🔗 Preprocessing Notebook:  
[Google Colab Link](https://colab.research.google.com/drive/1IMYnEpBDvVXengvaFD9IxG0SYvmBKY4v)

---

## 🏷️ Data Labelling
Sentiment labelling was performed using **GPT-3.5 Turbo** to classify comments as:
- Positive
- Negative

This approach was chosen due to GPT’s ability to understand:
- Informal language
- Slang and emojis
- Mixed Malay-English (Manglish) comments

🔗 Labelling Notebook:  
[Google Colab Link](https://colab.research.google.com/drive/1vJmKlveHF4hfoo1z0yr5DTm87Ic8IgsB)

---

## 📊 Exploratory Data Analysis
Key insights:
- Average views per video: **583,154**
- Average likes: **27,965**
- Average comments: **396**
- Strong engagement spikes during **Raya Aidilfitri**
- Moderate engagement during **Raya Haji**

📈 Influencer analysis showed that collaborations with influencers like **Fuji, Emma, Dato, and Zizan** generated significantly higher reach.

---

## 😊 Sentiment Analysis Results
- **75–80% positive sentiment**
- **20–25% negative sentiment**

This indicates a strong brand image with low reputational risk.

---

## 🤖 Predictive Modelling
Three models were evaluated using an 80/20 train-test split:

| Model | Accuracy |
|------|----------|
| Gradient Boosted Trees | **81.98%** |
| Support Vector Machine | 79.07% |
| Naive Bayes | 69.19% |

✅ **Chosen Model:** Gradient Boosted Trees  
It demonstrated the most balanced performance in detecting both positive and negative sentiment.

---

## 💡 Business Recommendations
- Leverage festive campaigns (especially Raya Aidilfitri & Raya Haji)
- Collaborate with high-performing and mid-tier influencers
- Focus on emotionally expressive and culturally relevant content
- Use sentiment monitoring to detect early negative trends

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, WordCloud
- Apify
- Google Colab
- GPT-3.5 Turbo

---

## 👩‍💻 Author
**Farah**  
Junior Software Developer / Data Enthusiast  
Malaysia 🇲🇾
