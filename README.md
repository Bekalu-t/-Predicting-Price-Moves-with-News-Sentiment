EDA and Statistical Analysis Project
This repository contains code and notebooks for performing Exploratory Data Analysis (EDA) and statistical analysis on a news dataset. The project focuses on understanding data patterns, extracting insights through descriptive statistics, text analysis, and time series analysis, and demonstrating statistical thinking.
Folder Structure

.vscode/: IDE settings
.github/workflows/: CI/CD pipeline configurations
src/: Source code for reusable modules
notebooks/: Jupyter notebooks for interactive EDA
tests/: Unit tests for the code
scripts/: Python scripts for data processing and analysis

Setup Instructions

Clone the repository:git clone https://github.com/<your-username>/eda-stats-project.git


Create and activate a virtual environment:python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


Install dependencies:pip install -r requirements.txt


Create a branch for your work:git checkout -b task-1



Running the Analysis

Run the main EDA script: python scripts/eda_analysis.py
Explore Jupyter notebooks in the notebooks/ folder for interactive analysis.

CI/CD
This project uses GitHub Actions for continuous integration. The unittests.yml workflow runs unit tests on every push to the task-1 branch.
Commit Guidelines

Commit at least three times a day with descriptive messages.
Example: git commit -m "Added descriptive statistics for headline lengths"

EDA Tasks

Descriptive Statistics:
Compute headline length statistics.
Count articles per publisher.
Analyze publication date trends.


Text Analysis:
Perform topic modeling to identify common keywords or phrases.


Time Series Analysis:
Analyze publication frequency over time.
Identify peak publishing times.


Publisher Analysis:
Identify top publishers and their news types.
Extract unique domains from email-based publisher names.



