# Student Performance Predictor

This is a simple Streamlit app that predicts a student's final grade (G3) using 5 key inputs:

- Study time
- Number of past class failures
- Absences
- First period grade (G1)
- Second period grade (G2)

## How it works

The app uses a trained Random Forest Regressor model (`model.pkl`) trained on the [UCI Student Performance dataset](https://archive.ics.uci.edu/ml/datasets/Student+Performance).

## How to run

Install dependencies:

```bash
pip install streamlit scikit-learn pandas numpy
streamlit run main.py
