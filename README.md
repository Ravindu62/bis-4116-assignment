# Bank Marketing Campaign Analysis

This repository contains a comprehensive data analysis of direct marketing campaigns (phone calls) of a Portuguese banking institution. The goal is to predict if the client will subscribe to a term deposit.

## Project Structure

- `REPORT.md`: The detailed analysis report, including findings, visualizations, and recommendations.
- `analysis.ipynb`: A Jupyter Notebook containing the Python code used for data loading, cleaning, and analysis.
- `bank.csv`: The dataset used for the analysis (sourced from Kaggle).
- `images/`: Directory containing the generated plots used in the report.

## Getting Started

### Prerequisites
To run the analysis code, you will need Python installed with the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- kagglehub

You can install them via pip:
```bash
pip install pandas numpy matplotlib seaborn kagglehub
```

### Running the Analysis
1.  Clone this repository.
2.  Open `analysis.ipynb` in Jupyter Notebook or JupyterLab.
3.  Run all cells to download the dataset and generate the analysis.

## Key Findings
- **Subscription Rate:** ~47.38% (in this dataset)
- **Top Driver:** Call Duration is the strongest predictor. Longer calls correlate strongly with subscription success.
- **Financial Impact:** Subscribers tend to have significantly higher account balances.
