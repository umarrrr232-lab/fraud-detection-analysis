# Fraud Detection & Risk Scoring System

## Overview
A fraud detection pipeline that analyzes 51,000 real transaction records, 
calculates a risk score for each one, and flags high-risk transactions 
using statistical outlier detection (Z-score method).

## The Problem
Manually reviewing thousands of transactions for fraud is slow and error-prone. 
This project automates the process — scoring every transaction and surfacing 
the ones most likely to be fraudulent, so analysts can focus their attention 
where it matters most.

## What It Does
- Cleans and processes 51,000 transaction records
- Calculates a fraud risk score per transaction
- Detects statistical outliers using Z-score analysis
- Ranks and outputs the top high-risk transactions for review

## Tech Stack
Python · Pandas · NumPy · (add Matplotlib/Seaborn if you used them for charts)

## Sample Output
<img width="985" height="683" alt="image" src="https://github.com/user-attachments/assets/b85a9a23-d050-47fb-bf83-2df0f73565a2" />


## Files
- `projectBDA.ipynb` — full analysis notebook
- `Fraud Detection Dataset.csv` — input data
- `fraud_detection_output.csv` — risk-scored output

## Key Insight
- 48,490 normal transactions vs 2,510 fraud (only 4.9% fraud — class imbalance)
- Fraudulent transactions had a slightly higher average amount (3088 vs 2966)
- Online Purchase and Bill Payment had the most fraud cases
- Mobile devices were used most in fraud
- UPI had the highest fraud count among payment methods
