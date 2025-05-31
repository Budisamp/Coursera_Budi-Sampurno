# Weight Lifting Exercise Quality Prediction

This project uses machine learning to predict how well participants perform weight lifting exercises based on accelerometer data.

## Project Overview
- **Goal**: Predict exercise quality (classe A-E) using sensor data
- **Data Source**: [Groupware@LES](http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har)
- **Training Data**: [pml-training.csv](https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv)
- **Test Data**: [pml-testing.csv](https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv)

## Files
- `weightlifting_analysis.Rmd`: Main analysis file
- `weightlifting_analysis.html`: Compiled report
- `predictions.txt`: Test case predictions
- `functions.R`: Helper functions

## How to Reproduce
1. Clone this repository
2. Open `weightlifting_analysis.Rmd` in RStudio
3. Install required packages
4. Knit to HTML
