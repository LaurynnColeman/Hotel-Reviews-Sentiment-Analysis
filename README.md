# **Hotel Reviews NLP Sentiment Analysis**

## **Overview**
This project applies **Natural Language Processing (NLP)** techniques to analyze **hotel reviews** and classify sentiments. By leveraging **NLTK's Vader** and **Hugging Face's DistilBERT**, the goal is to extract insights that help businesses improve customer satisfaction and service quality.

## **Why This Matters**
- **Hotels rely on customer feedback** to enhance experiences and increase bookings.
- **Manually analyzing thousands of reviews** is inefficient—NLP automates this process.
- **Sentiment insights drive data-informed decisions** for hospitality businesses.

## **Key Results**
- **Achieved 89% model accuracy** in sentiment classification.
- **Identified top and bottom-rated hotels** based on sentiment analysis.
- **Provided business insights** to optimize hotel services.

## **Dataset**
- **Source**: [Kaggle - 515K Hotel Reviews in Europe](https://www.kaggle.com/datasets/jiashenliu/515k-hotel-reviews-data-in-europe)
- **Contents**: Reviews from various hotels across Europe with customer ratings and textual feedback.

## **Methodology**
### **1. Sentiment Analysis Approaches**
#### **NLTK (Vader)**
- Utilized **SentimentIntensityAnalyzer()** to assign sentiment scores.
- Provides a **rule-based** approach for quick analysis.
- **Limitations**: Struggles with nuanced language and context.

#### **DistilBERT (Hugging Face)**
- Used **distilbert-base-uncased-finetuned-sst-2-english** for sentiment classification.
- Captures deeper **contextual meaning** in text.
- **Outperformed NLTK** in classification accuracy.

### **2. Insights Generated**
- **Identified top and bottom hotels** based on review sentiment.
- **Extracted common words** in reviews to understand guest concerns and praises.
- **Visualized sentiment distributions** for better interpretability.

## **Business Impact**
- **Hotels can prioritize service improvements** based on customer sentiment.
- **Marketing strategies can be refined** using sentiment trends.
- **Operational efficiency is enhanced** by focusing on key feedback themes.

For a detailed walkthrough of the analysis, view the full presentation:
[View the full presentation here](Hotel%20Reviews%20NLP%20Presentation.pdf)

### If you have suggestions for enhancing the code or the project overall, please feel free to open an issue or submit a pull request. Your contributions are greatly appreciated!
