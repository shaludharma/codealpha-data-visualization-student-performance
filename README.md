# Student Performance - Data Visualization

This project is part of my **CodeAlpha Data Analytics Internship**.
I created visualizations on the Students Performance in Exams dataset to understand how different factors relate to student scores.

## Dataset
- 1000 students, 8 columns
- Columns: gender, race/ethnicity, parental level of education, lunch, test preparation course, math score, reading score, writing score

## Tools Used
- Python
- pandas
- matplotlib
- seaborn
- Google Colab

## Visualizations Created
1. Bar chart: average scores by gender
2. Bar chart: average scores by test preparation course
3. Histogram: distribution of math scores
4. Box plot: math score by lunch type
5. Count plot: students by parental education level
6. Scatter plot: math score vs reading score
7. Heatmap: correlation between scores

## Key Findings
- Male students scored higher in math; female students scored higher in reading and writing
- Students who completed the test preparation course scored higher in all three subjects
- Students with standard lunch had higher math scores than students with free/reduced lunch
- Math, reading and writing scores are strongly correlated (reading and writing: 0.95)

## How to Run
1. Open the notebook in Google Colab
2. Upload `StudentsPerformance.csv`
3. Run all cells
