# STAT5243 Project 3

This repository contains the code for **Columbia University STAT GR5243 Project 3**.

## Files

- `app.py`  
  Original Shiny app from Project 2.

- `app_left.py`  
  Left-layout version of the app with embedded GA4 scripts for event tracking.

- `app_right.py`  
  Right-layout version of the app with embedded GA4 scripts for event tracking.

- `data_analysis.ipynb`  
  Notebook used for data analysis.

## Description

For this project, the original Shiny app from Project 2 was adapted into two versions with different UI layouts. The purpose is to compare user behavior across the two designs using Google Analytics 4 event tracking.

Both `app_left.py` and `app_right.py` send user interaction events and labels to GA4, which can then be analyzed in `data_analysis.ipynb`.

## Requirements

Install dependencies with: requirements.txt
