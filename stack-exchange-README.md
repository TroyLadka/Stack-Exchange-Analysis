# Stack Exchange Data Analysis

## Project Overview
A comprehensive data analysis of Stack Exchange platform interactions, focusing on question-answer dynamics, user behaviors, and platform engagement metrics.

## Key Findings
- Acceptance rate for answers is approximately 50%
- Most questions and answers have scores between 0-5
- Moderate correlation between question scores and number of answers (0.584)
- Programming languages like Python, C++, Java dominate platform tags

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- SciPy

## Data Sources
- `codereview-questions.csv`
- `codereview-answers.csv`

## Analysis Techniques
- Descriptive Statistics
- Correlation Analysis
- Tag Frequency Analysis
- Time Series Visualization

## Project Structure
```
stack-exchange-analysis/
│
├── data/
│   ├── codereview-questions.csv
│   └── codereview-answers.csv
│
├── stack_exchange_analysis.py     # Main analysis script
├── moments.csv                    # Calculated statistical moments
├── visualization/
│   ├── daily_posts.png
│   ├── histogram.png
│   └── question_scores_vs_answer_scores.png
│
└── README.md
```

## Visualizations
1. Daily Posts Trend
2. Question & Answer Score Histograms
3. Question Scores vs Answer Scores Scatter Plot

## How to Reproduce
1. Clone the repository
2. Install required dependencies:
   ```
   pip install pandas numpy matplotlib scipy
   ```
3. Run the analysis script:
   ```
   python stack_exchange_analysis.py
   ```


