# DSS5201 Group Project: Coffee Consumption, Preferences, and Spending

## Research Question

How are coffee drinking habits, brewing preferences, and self-rated coffee expertise associated with monthly coffee spending and willingness to pay among respondents in the coffee survey?

## Dataset

**The Great American Coffee Taste Test** from [TidyTuesday (2024-05-14)](https://github.com/rfordatascience/tidytuesday/tree/main/data/2024/2024-05-14).
The survey contains 4,042 responses and 57 variables covering demographics, brewing methods, favorite drinks, roast preferences, coffee expertise, and spending behavior.

## Project Structure

```
DSS5201/
├── data/
│   └── coffee_survey.csv              # Raw survey data
├── output/
│   └── jupyter-notebook/
│       ├── coffee_project_report.ipynb # Main report notebook
│       └── coffee_project_report.html  # Exported HTML report
├── scripts/
│   └── build_coffee_project_notebook.py
├── README.md
└── requirements.txt
```

## Visualizations

The report contains three figures:

1. **Faceted Heatmap** — Spending shifts upward as daily coffee consumption increases, compared across work arrangements (Home / Hybrid / In person).
2. **Bubble Chart** — Espresso-leaning preference clusters (brewing method x favorite drink) are more likely to include high spenders.
3. **Grouped Boxplot** — Higher self-rated expertise aligns with higher willingness to pay, especially for light-roast drinkers.

## Setup and Reproduction

```bash
# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook output/jupyter-notebook/coffee_project_report.ipynb
```

The notebook will automatically load data from `data/coffee_survey.csv` if present, or fall back to downloading from the TidyTuesday GitHub repository.

## References

1. TidyTuesday. (2024, May 14). *The Great American Coffee Taste Test*. https://github.com/rfordatascience/tidytuesday/tree/main/data/2024/2024-05-14
2. Hoffmann, J. (2023). *The Great American Coffee Taste Test* [Video]. YouTube. https://www.youtube.com/watch?v=bMOOQfeloH0
