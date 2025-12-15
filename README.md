# ML Spend Classifier

## Overview
Procurement teams often struggle with messy data where purchase descriptions (e.g., "UBER *TRIP 829") aren't categorized. This project uses Machine Learning to automatically classify spend data into categories (IT, Travel, Marketing, etc.).

## Tech Stack
*   **Python**
*   **Scikit-Learn** (Random Forest Classifier)
*   **Pandas** (Data Manipulation)
*   **Seaborn** (Visualization)

## How it works
1.  **Data Ingestion:** Takes raw description data.
2.  **NLP Processing:** Uses TF-IDF to convert text to numerical vectors.
3.  **Classification:** Predicts the category using a Random Forest model.
4.  **Reporting:** Visualizes total spend by category.

## How to Run
1.  Install requirements: `pip install -r requirements.txt`
2.  Open `spend_analysis.ipynb` in VS Code or Jupyter.

3.  Run all cells.

