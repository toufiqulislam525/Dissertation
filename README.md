# Dissertation Code Repository

This repository contains the Python notebooks used for the dissertation:

**Volatility as a Moderator of News Sentiment Predictive Power**

The notebooks document the full development workflow, including data construction, feature engineering, exploratory analysis, statistical interaction testing, prediction modelling, table generation, and rejected/experimental approaches.

## Folder Structure

### 01_main_workflow
Contains the main data preparation notebooks:
- S&P 500 membership panel construction
- price data download
- Bloomberg sentiment processing
- sentiment-price merging
- feature engineering

### 02_analysis_and_models
Contains the main analysis notebooks:
- exploratory data analysis
- logistic regression interaction testing
- final prediction modelling

### 03_tables_and_results
Contains notebooks used to prepare and store tables, figures, and result summaries used in the dissertation.

### 04_experiments_and_rejected_approaches
Contains trial, experimental, and rejected modelling approaches, including technical indicators, earlier logistic regression trials, LSTM trials, and alternative prediction model attempts.

## Data Availability

Raw Bloomberg data files are not included in the repository because they were accessed through Northumbria University's institutional Bloomberg Terminal licence. Therefore, the repository is not presented as a fully self-contained reproduction package. Instead, it is provided as a code audit trail showing the analytical steps, modelling attempts, and development process used to produce the dissertation results.

## Main Outputs

The main outputs from this workflow include:
- cleaned S&P 500 membership panel
- processed Bloomberg sentiment dataset
- merged sentiment-price dataset
- final modelling dataset
- EDA figures and tables
- interaction test results
- robustness checks
- prediction model results
- rejected approach results
