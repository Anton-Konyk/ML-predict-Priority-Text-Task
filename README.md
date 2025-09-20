"# ML-predict-Priority-Text-Task" 

## Description
This project trains a simple text classification model that predicts 
the **priority** of employee tasks (`high` / `low`) based on their 
description. It is intended as a test example to demonstrate skills in Python,
Jupyter Notebook, Pandas, ML libraries, and integration.

## Installation
Create and activate virtual environment (optional, but recommended):

```bash
git clone https://github.com/Anton-Konyk/ML-predict-Priority-Text-Task
cd ML_predict_priority_text_task
python -m venv .venv
source .venv/bin/activate   # Linux/Mac
.venv\Scripts\activate      # Windows
pip install -r requirenents.txt
```

## Incoming data structure
The model requires a CSV file with tasks and their priorities (high or low).
Example:
[tasks.csv](tasks.csv)

## Result
Model saved as model.pkl
Vectorizer saved as vectorizer.pkl
