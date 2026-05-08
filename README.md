# Cyber Threat Detection using NLP

An NLP-based system that automatically detects and classifies cyber threats from unstructured text data — achieving 85% accuracy.

## What it does
- Scans text data for malicious patterns and cyber threats
- Classifies threats into categories using ML algorithms
- Uses TF-IDF for feature extraction from raw text

## Tech Stack
- Python, scikit-learn, pandas, NumPy
- TF-IDF Vectorizer
- Machine Learning Classification (Logistic Regression / Random Forest)
- Flask (web interface)
- SQL database

## Results
- Accuracy: 85%
- Dataset: Real-world annotated cyber threat text data

## How to run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run: `python app.py`

## Project Structure
- `Notebook.ipynb` — Full ML pipeline (data prep → model → evaluation)
- `app.py` — Flask web application
- `annotated.xls` — Training dataset
