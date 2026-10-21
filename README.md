# Cyber Threat Detection using NLP | Applicable to OT Logs & DCS Alarms @ Yokogawa

An NLP-based system that automatically detects and classifies cyber threats from unstructured text data — achieving 85% accuracy.

**Yokogawa Context:** Same approach can be extended to analyze DCS CENTUM VP alarm logs, Exaquantum Historian data & Taurob inspection reports for anomaly & threat detection to reduce downtime.

## What it does
* Scans text data for malicious patterns and cyber threats
* Classifies threats into categories using ML algorithms
* Uses TF-IDF for feature extraction from raw text

## Tech Stack
* Python, scikit-learn, pandas, NumPy
* TF-IDF Vectorizer
* Machine Learning Classification (Logistic Regression / Random Forest)
* Flask (web interface)
* SQL database

## Results
* Accuracy: 85%
* Dataset: Real-world annotated cyber threat text data

## Industrial Application @ Yokogawa
* DCS alarm logs & Historian trends can be treated as text data for anomaly detection
* Predictive Maintenance alerts using NLP on maintenance logs
* Foundation for RAG-based Document Assistant for FKDPP manuals

## How to run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run: `python app.py`

## Project Structure
- `Notebook.ipynb` — Full ML pipeline (data prep → model → evaluation)
- `app.py` — Flask web application
- `annotated.xls` — Training dataset
