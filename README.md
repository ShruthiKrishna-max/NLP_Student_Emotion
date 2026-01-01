# Student Emotion Analysis Using NLP

[![Python](https://img.shields.io/badge/python-3.12-blue?logo=python&logoColor=white)](https://www.python.org/)

## Project Overview
This project analyzes student feedback using Natural Language Processing (NLP) to detect emotions, classify sentiment, and generate actionable suggestions. It helps institutions gain meaningful insights from unstructured feedback efficiently, enabling data-driven academic improvements.

---

## Dataset
- **Source:** Student feedback dataset (manually curated)  
- **Size:** 100 feedback entries  
- **Features:**
  - `feedback_text`: Original student feedback  
  - `emotion`: Detected emotion (e.g., Confused, Motivated, Stressed)  
  - `topic`: Related topic (e.g., Lectures, Assignments, Exams)  
  - `sentiment`: Positive, Neutral, Negative  
  - `intensity_score`: Numeric representation of emotion intensity  
- **Preprocessing:** Text cleaning, lowercasing, TF-IDF feature extraction

---

## Methodology
1. **Text Preprocessing:** Clean and tokenize feedback.  
2. **Feature Extraction:** Convert text to numerical vectors using TF-IDF.  
3. **Emotion Classification:** Classify feedback into 12 emotion categories.  
4. **Sentiment Analysis:** Classify as Positive, Neutral, or Negative.  
5. **Auto-Generated Suggestions:** Generate actionable feedback based on emotion + topic.  
   - Example: "Students feel confused about the pace → Consider slower explanations and more examples."  
6. **Visualization:**  
   - Emotion distribution bar chart  
   - Boxplot of intensity vs sentiment  
   - Word cloud of top words  
   - Confusion matrix for model evaluation

---

## Results
- **Accuracy:** ~85% on test set  
- **Classification Report & Confusion Matrix:** Shows performance per sentiment class  
- **Top TF-IDF Words:** `feel`, `assignments`, `course`, `anxious`, `satisfied`  
- **Key Insight:** The system not only detects sentiment but also provides actionable suggestions, making feedback truly useful for academic improvement.

---

## Conclusion
This NLP project demonstrates how student feedback can be transformed into actionable insights. By combining emotion detection, sentiment analysis, and topic-based suggestions, the system helps institutions identify areas for improvement and enhances the overall academic experience.

---

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/Shruthi/student-emotion-nlp.git
