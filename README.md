# SpaceX Falcon 9 First-Stage Landing Prediction

IBM Data Science Professional Certificate capstone project analyzing and predicting Falcon 9 first-stage landing success.

## Project workflow

1. SpaceX API data collection
2. Wikipedia web scraping
3. Data wrangling and landing outcome labels
4. Exploratory data analysis with visualization
5. SQL analysis
6. Folium launch-site mapping
7. Plotly Dash interactive dashboard
8. Machine learning model comparison

## Key findings

- The prepared dataset contains 90 Falcon 9 launches from 2010 to 2020.
- The landing-success label has an 87.8% success share.
- KSC LC-39A accounts for 41.7% of successful launches in the all-sites dashboard.
- Logistic regression, SVM, decision tree, and KNN each achieved 83.3% test accuracy.
- The decision tree achieved the strongest cross-validation accuracy at 92.9%.

## Repository structure

- `notebooks/` - completed and executed Jupyter notebooks
- `dashboard/` - Plotly Dash application, required CSV dataset, and screenshots
- `maps/` - exported interactive Folium map
- `final-deliverables/` - single final presentation-style PDF submitted for grading

## Final deliverables

Upload `final-deliverables/Data_Science_Capstone_Project_Report.pdf` to the IBM final assignment. The PDF follows rubric items 1.1-1.15 in order and contains the project URL, methods, required result charts, model evaluation, and conclusion. Editable local source files are intentionally excluded from this grading repository.

