# Machine Learning-Based Network Intrusion Detector

**Student:** Trupti Devanand Salunkhe  
**Institute:** Sandip University, Nashik  
**Program:** B.Sc. Forensic Science — Third Year  
**Program context:** IBM SkillsBuild Cyber Security 2026 / BharatCares

## Overview
This educational prototype uses a Random Forest classifier to label network-traffic records as **normal** or **suspicious**. It demonstrates a basic machine-learning workflow relevant to cyber security and digital forensics: data preparation, model training, evaluation, and interpretation.

## Important scope note
The notebook generates a clearly labelled **synthetic demonstration dataset** so it runs without a large download or external service. Synthetic data is useful for demonstrating the workflow, but it does **not** prove real-world detection performance. For a research extension, evaluate the model on a suitable public dataset such as CIC-IDS2017 or UNSW-NB15, following the dataset provider's terms and documentation. Results from this demo must not be presented as validated production performance.

## Features
- Reproducible synthetic network-flow demo data
- Train/test split with stratification
- Random Forest classifier
- Accuracy, precision, recall, F1-score, and confusion matrix
- Feature-importance chart
- Ethical and forensic limitations discussion

## Files
- `Trupti_Salunkhe_ML_Network_Intrusion_Detector.ipynb` — complete Jupyter Notebook
- `requirements.txt` — Python dependencies
- `Trupti_Salunkhe_ProjectReport.docx` — project documentation
- `network_intrusion_detector.py` — runnable Python script
- `README.md` — this guide

## Setup
Use Python 3.10 or later. In a terminal, from this project folder:

```bash
python -m venv .venv
```

Activate the environment:

- Windows: `.venv\\Scripts\\activate`
- macOS/Linux: `source .venv/bin/activate`

Install dependencies:

```bash
pip install -r requirements.txt
```

## Run the notebook
```bash
jupyter notebook
```
Open `Trupti_Salunkhe_ML_Network_Intrusion_Detector.ipynb` and choose **Run All**.

## Run the Python script
```bash
python network_intrusion_detector.py
```

## Example interpretation
The script prints evaluation metrics calculated from the generated synthetic dataset. Metrics can vary if the data-generation logic is changed. Do not interpret these results as an estimate of performance on live networks.

## GitHub publication
1. Sign in to GitHub and create a **public** repository named `ml-network-intrusion-detector`.
2. Upload the files in this folder (or extract the supplied ZIP first).
3. Add a repository description such as: `Educational ML prototype for network intrusion detection`.
4. Confirm the notebook, report, README, and requirements file are visible.
5. Copy the repository URL from the browser and include it in your submission.

Never upload passwords, API keys, private traffic captures, personal data, or confidential institutional information.
