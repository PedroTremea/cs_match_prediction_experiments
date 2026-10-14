# CS2 Match Prediction

Statistical modeling and machine learning for predicting Counter-Strike 2 match outcomes 

# Research question

How much do Valve Regional Standings (VRS) and HLTV rankings improve the predictive performance of statistical models for professional Counter-Strike 2 matches?

# Objectives

Build a reproducible dataset of historical CS2 matches.

Establish a baseline model using historical match results and rating-based features.

Investigate whether VRS information improves predictive performance.

Explore additional features extracted from match demo files.

Evaluate predictions using probabilistic metrics.

Quantify the incremental predictive value of VRS and HLTV rankings, individually and jointly.

# Methodology

The project will progress through the following stages:

Data collection and documentation.

Data cleaning and exploratory analysis.

Baseline model development.

Feature engineering and model comparison.

Chronological validation and evaluation.

Interpretation of results and limitations.

# Evaluation

Planned evaluation metrics include:

Log loss: evaluates the quality of predicted probabilities.

Brier score: measures the squared error of probabilistic predictions.

Calibration: assesses whether predicted probabilities correspond to observed frequencies.

Model evaluation will respect the chronological order of matches. Features will only use information available at the prediction time.

# Project structure

src/: main project code.

tests/: automated tests.

notebooks/: exploratory analyses.

docs/: research notes and methodology.

data/: local datasets, when needed.

Data and reproducibility



# Current status

Initial development environment configured. Research design and data pipeline are under development.

# Author

Research project developed as part of an undergraduate-level study in statistical modeling and machine learning.