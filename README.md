# DSS5201 Group Project: Coffee Consumption, Preferences, and Spending

## Research Question

What demographic, taste-preference, and self-rated expertise factors are associated with higher coffee spending among respondents in the Great American Coffee Taste Test survey?

## Dataset

**The Great American Coffee Taste Test** from [TidyTuesday (2024-05-14)](https://github.com/rfordatascience/tidytuesday/tree/main/data/2024/2024-05-14).
The survey contains 4,042 responses and 57 variables covering demographics, brewing methods, favorite drinks, roast preferences, coffee expertise, and spending behavior.

## Project Structure

```
DSS5201/
├── data/
│   └── coffee_survey.csv              # Raw survey data
├── coffee_project_report.ipynb        # Main report notebook
├── coffee_project_report.html         # Exported HTML report
├── coffee_project_report.pdf          # Exported PDF report
├── README.md
└── requirements.txt
```

## Visualizations

The report contains three figures, each addressing one sub-question:

1. **Grouped Bar Chart** — Share of respondents spending ≥ $60/month on coffee, by age group and education level.
2. **Heatmap** — Average monthly coffee spending across the 5 × 5 matrix of home brewing methods and favorite drinks.
3. **Line Chart** — Share of respondents with high equipment investment (≥ $500) and high monthly spending (≥ $60), plotted against self-rated coffee expertise (1–10).

## Setup and Reproduction

```bash
# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook coffee_project_report.ipynb
```

The notebook will automatically load data from `data/coffee_survey.csv` if present, or fall back to downloading from the TidyTuesday GitHub repository.

## References

1. TidyTuesday. (2024, May 14). *The Great American Coffee Taste Test*. https://github.com/rfordatascience/tidytuesday/tree/main/data/2024/2024-05-14
2. Hoffmann, J. (2023). *The Great American Coffee Taste Test* [Video]. YouTube. https://www.youtube.com/watch?v=bMOOQfeloH0
