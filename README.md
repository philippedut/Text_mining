# **Text mining: SENTIMENT ANALYSIS**

This repository contains the implementation of a Sentiment Analysis project, where we predict market sentiment (Bearish, Bullish, or Neutral) from tweets using NLP techniques.

---

## 🎓 Master’s Program in Data Science & Advanced Analytics  
**Nova IMS** | Spring Semester 2025  
**Course:** Text Mining

## 👥 Team **Group 34**  
- **[Diogo Duarte]** | [20240525]
- **[Philippe Dutranoit]** | [20240518]  
- **[Rodrigo Sardinha]** | [20211627]
- **[Rui Luz]** | [20211628]

## 📂 **Folder Structure**  
- `report_34.pdf` contains the report written for this project
- CSV files with the dataset can be found in **Data** folder, while code can be found in the folder **Notbooks**
- `pred_34.csv` contains the predicted label achieved using the final model
- `tm_exploratory_34.ipynb` contains all steps taken during EDA
- `tm_final_34.ipynb` contains the final model tuning and evaluation
- `tm_tests_01_34.ipynb` contains tests made using frequency based approaches with classic classifiers
- `tm_tests_02_34.ipynb` contains tests made using LSTM models
- `tm_tests_04_34.ipynb` contains tests made using Pre-trained Transformer Models (BERT)

### Notes

⚠️ Note: The GloVe embeddings file `glove.twitter.27B.100d.txt` must be manually placed in the `Data` folder.  
The file is not included in this repository due to size limitations (>100MB).  
Download from: https://nlp.stanford.edu/projects/glove/
