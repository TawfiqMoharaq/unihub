# 🧠 UniHub — Smart University Activity Recommender

**UniHub** is an AI-powered platform designed to help university students discover and join activities that best match their **interests, academic profile, and skills**.  
The system leverages **Machine Learning, NLP, and Recommendation Models** to deliver personalized event suggestions and notifications.

---

## 🚀 Overview

Many students miss out on valuable extracurricular or academic events because they don’t know which ones fit their interests.  
**UniHub** solves this by analyzing both **student profiles** and **event metadata** to recommend suitable opportunities.

---

## 🧩 Key Features

- 🎯 **Personalized Event Recommendations**  
  Suggests suitable university activities based on each student’s major, interests, and level.

- 🔔 **Smart Event Notifier (AI-based)**  
  Uses semantic similarity and XGBoost classification to identify relevant events and notify the right students.

- 📊 **Data-driven Insights**  
  Generates analytical dashboards to monitor engagement and participation.

- 💬 **Natural Language Understanding**  
  Uses embedding models (SentenceTransformer, TF-IDF) to understand meaning beyond keywords.

---

## ⚙️ Tech Stack

| Category | Tools / Libraries |
|-----------|------------------|
| **Language** | Python 3.12 |
| **ML Models** | XGBoost, RandomForest, Logistic Regression |
| **NLP / Embeddings** | SentenceTransformer (`all-MiniLM-L6-v2`), TF-IDF |
| **Visualization** | Matplotlib, Seaborn |
| **Data Handling** | Pandas, NumPy, Scikit-learn, Imbalanced-learn (SMOTE) |
| **IDE** | Google Colab & Visual Studio Code |

---

## 🧠 Model Workflow

1. **Data Generation** — Synthetic dataset of students, majors, and university events.  
2. **Semantic Labeling** — Calculates similarity between student interests and event titles using embeddings.  
3. **Model Training** — XGBoost learns patterns of which events each student is likely to attend.  
4. **Evaluation** — Precision, Recall, F1, ROC-AUC, and PR-AUC used for performance comparison.  
5. **Notifier System** — Predicts which students should be notified about upcoming events.
