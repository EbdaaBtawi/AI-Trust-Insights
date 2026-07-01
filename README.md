# AI Trust Insights

Analyzing user trust in AI-generated responses across 6 models and 12 query categories.

## Overview
- Dataset: 1,000 responses rated by real users (Kaggle)
- Models analyzed: Claude, GPT-4, Gemini, ChatGPT-3.5, Llama, Mistral

## What We Did
- Missing value imputation (935 cells)
- Outlier detection via IQR & boxplots
- Feature scaling: MinMaxScaler & RobustScaler
- Dimensionality reduction: PCA (99.42% variance retained)
- Feature selection: RFE (top 3 features)
- Encoding: One-Hot & Label Encoding

## Key Finding
AI confidence is the strongest predictor of user trust:
- Confidence ↔ Accuracy: r = 0.86
- Confidence ↔ Trust: r = 0.70

## Tools
Python · Pandas · Scikit-learn · Matplotlib · Seaborn

## Team 
Ebdaa Btawi · Eejab Ali · Ensherah Alghamdi · Dina Rummani · Nouf bin Taleb · Rivan Alnabati

## Supervisor
Project completed as part of Data Collection and Preprocessing under the supervision of Dr. Maram Barifah 

*Completed at Umm Al-Qura University — College of Computing*
