# Student Feedback Analysis Using Natural Language Processing (NLP) and Sentiment Analysis  

---

## Overview  

This repository contains the code for analyzing student feedback using NLP and Sentiment Analysis.  
A fine-tuned DistilRoBERTa (BERT-based) model is used to classify feedback into positive, neutral, and negative sentiments.  

---

## Model  

| Model | Type | Description |
|------|------|------------|
| DistilRoBERTa | Fine-tuned | Transformer-based model for sentiment classification |

---

## Repository Structure  

```
Sentiment_Analysis_BERT/
├── data/
├── models/
├── scripts/
├── utils/
├── results/
├── notebooks/
├── requirements.txt
└── README.md
```

---

## Setup  

```
git clone https://github.com/sharmin3036/Sentiment_Analysis_BERT.git
cd Sentiment_Analysis_BERT
pip install -r requirements.txt
```

---

## Dataset  

- 377 student comments  
- Labels: Positive, Neutral, Negative  

---

## Methodology  

1. Data preprocessing  
2. Annotation (manual + model)  
3. Data augmentation (back-translation)  
4. Model fine-tuning  
5. Evaluation (Accuracy, F1, etc.)  

---

## Results  

- Accuracy: 90%  
- Pearson Correlation: 0.42  
- Regression Coefficient: 0.24  

---
## Citation
@inproceedings{badhan2025board,
  title={BOARD\# 56A: Student Feedback Analysis Using Natural Language Processing (NLP) and Sentiment Analysis},
  author={Badhan, Sharmin Jahan and Samsami, Rei and Nossoni, Goli},
  booktitle={2025 ASEE Annual Conference \& Exposition},
  year={2025}
}
## Publication
Badhan, Sharmin Jahan, Rei Samsami, and Goli Nossoni. "BOARD# 56A: Student Feedback Analysis Using Natural Language Processing (NLP) and Sentiment Analysis." In 2025 ASEE Annual Conference & Exposition. 2025. 
This work applies natural language processing (NLP) and sentiment analysis to student feedback data, enabling quantitative insights from qualitative course evaluations. The study supports data-driven improvements in teaching effectiveness and educational assessment.
- [Read Full Paper](https://doi.org/10.18260/1-2--56002)

## Authors  

- Sharmin Jahan Badhan  
- Reihaneh Samsami  
- Goli Nossoni  

---
