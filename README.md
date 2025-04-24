## Predicting Myers-Briggs Types with Cognitive Functions and Text Input

This Independent Study project applies supervised machine learning, specifically Support Vector Machines (SVM) and Logistic Regression, to classify Myers-Briggs personality types based on forum text. Instead of using the four-letter MBTI format, this project uses cognitive function theory, as introduced by Carl Jung and further developed by John Beebe, to model six different function-based classification schemes.

## 📁 Data

The dataset used is sourced from Kaggle:
https://www.kaggle.com/datasets/zeyadkhalid/mbti-personality-types-500-dataset

Due to size constraints, the full dataset is not included in this repository. It contains user-generated posts labeled by MBTI type, which were transformed into new labels based on function theory.

![image](https://github.com/user-attachments/assets/acc03f87-bc92-40c9-8119-aaf753e7071a)

---

## 🧠 Function-Based Classification Targets

Six classification tasks were created by mapping MBTI types to their respective cognitive functions:

- **Rational functions** (`rationals`) – binary: thinking vs. feeling
- **Irrational functions** (`irrationals`) – binary: intuition vs. sensing
- **Dominant rational function** (`rat_dominant`) – 4-class: Fe, Fi, Te, Ti
- **Dominant irrational function** (`irrat_dominant`) – 4-class: Ne, Ni, Se, Si
- **Dominant function** (`dominant`) – 8-class: all dominant function types
- **Auxiliary function** (`auxiliary`) – 8-class: all auxiliary function types

---

## 🛠️ Methods

- Preprocessing: stopword removal, MBTI vocabulary filtering, lemmatization (NLTK)
- Feature extraction: TF-IDF vectorization
- Models: Logistic Regression and Linear SVM
- Evaluation: Accuracy and F1-score (micro average)
- Visualization: Confusion matrices for key models

---

## 📄 Files

- `MBTI_Modeling.ipynb` — Jupyter notebook containing full workflow
- `/figures/` — Confusion matrices and other visuals
- `README.md` — This file

---

## 📝 Notes

This project was completed as part of a Junior Independent Study at The College of Wooster and will serve as the foundation for a Senior IS exploring survey-based validation or real-time function prediction.
