# 🎓 Buddy Recommendation System

A machine learning–based **Buddy Recommendation System** designed for the Dean’s Office to help students find compatible study partners.  
The system uses students’ teamwork preferences, personality traits, hobbies, and club interests to recommend study buddies.

---

## 🚀 Problem Statement
Students often struggle to find the right study partners, impacting collaborative learning outcomes.  
This project builds a **data-driven recommendation system** that suggests compatible buddies to improve learning and engagement.

---

## 📊 Features
- Cleans and preprocesses messy survey data (handling text, ranges, and missing values).
- Encodes categorical features (clubs, hobbies) using **One-Hot Encoding**.
- Normalizes numerical features with **StandardScaler**.
- Computes similarity using **Cosine Similarity**.
- Evaluates system performance with **Precision@K** and **Recall@K**.
- Includes visualization: similarity heatmap & Precision@K trend.

---

## ⚙️ Methods
1. **Data Preprocessing**  
   - Cleaned unstructured survey data.  
   - Converted ranges like `9-10` → `9` and handled non-numeric entries.  
   - Applied scaling and encoding for uniformity.  

2. **Model**  
   - **Content-based recommendation** using cosine similarity.  
   - Recommendation = Top-K most similar students.  

3. **Evaluation**  
   - **Precision@K** → proportion of relevant buddies in top-K.  
   - **Recall@K** → proportion of relevant buddies retrieved.  
   - Visualized results to analyze trends in recommendation quality.

---

## 📈 Results & Insights
- **High Precision at low K (≈1.0)** → very accurate top buddy matches.  
- **Precision declines as K increases** → because each student has only a limited pool of highly compatible buddies.  
- **Interpretability** → Recommendations are transparent since features (teamwork, hobbies, clubs) directly explain compatibility.  


