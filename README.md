# EmotionDetectorMicroBlogs_SMOTE
# 💬 Emotion Detection from Twitter using AI & Genetic Algorithm

Understanding emotions from social media is crucial for behavioral analysis, mental health monitoring, and sentiment-based decision making. This project leverages **AI-driven Natural Language Processing (NLP)** and **Genetic Algorithms** to detect emotions from Twitter data with improved accuracy.

---

## 🎯 Objective

This project aims to:
- **Extract emotions** (e.g., joy, anger, sadness) from tweets using NLP.
- Introduce a **novel feature representation technique** for better emotional state capture.
- Use **Genetic Algorithm (GA)** to optimize feature input for maximum classification performance.
- Evaluate performance of various ML models and ensembles.

---

## 🧠 Methodology

### 🔹 Feature Representation
- A **custom representation method** was introduced to enhance the expressiveness of tweet features.
- Optimized via **Genetic Algorithms** for feature selection and tuning.

### 🔹 Machine Learning Models
The following classifiers were tested:
- ✅ Random Forest (RF)
- ✅ Support Vector Machine (SVM)
- ✅ K-Nearest Neighbors (KNN)
- ✅ XGBoost

Each classifier was:
- **Combined with Decision Trees** for improved decision-making power.
- Optimized using **cross-validation**, **grid search**, and **ensemble techniques**.
- Final ensemble was guided by **Genetic Algorithm** for feature and model tuning.

---

## 📈 Results

- The proposed approach showed **notable improvement in emotion detection accuracy**.
- Genetic Algorithm-based ensemble outperformed individual models in most metrics.
- Feature representation combined with GA enabled better generalization on unseen tweets.

---

## 🛠️ Tech Stack

- **Languages**: Python
- **Libraries**: 
  - scikit-learn
  - NLTK / spaCy
  - XGBoost
  - DEAP (for Genetic Algorithms)
- **Tools**: Jupyter Notebook, Google Colab

---


