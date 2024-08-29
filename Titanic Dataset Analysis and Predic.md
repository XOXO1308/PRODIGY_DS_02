# Titanic Dataset Analysis and Prediction

## Overview
This notebook performs a comprehensive analysis of the Titanic dataset, focusing on data cleaning, exploratory data analysis (EDA), and identifying patterns and trends. The analysis is aimed at uncovering insights that could aid in predictive modeling or decision-making related to the Titanic disaster.

## Features
1. **Data Cleaning:**
   - Handling missing values using `SimpleImputer`, filling numerical columns with the mean and categorical columns with the most frequent value.
   - Identifying and removing duplicate rows to ensure data integrity.

2. **Exploratory Data Analysis (EDA):**
   - **Distributions:** Visualizing distributions of numerical variables using histograms.
   - **Outliers Detection:** Using box plots to detect outliers in numerical columns.
   - **Relationships:** Exploring relationships between numerical variables using pair plots and a correlation matrix.
   - **Categorical vs. Numerical Analysis:** Examining relationships between categorical and numerical variables through box plots.

3. **Exploring Relationships Between Variables:**
   - **Scatter Plots:** Visualizing relationships between pairs of numerical variables.
   - **Correlation Matrix:** Providing a comprehensive overview of correlations between numerical features.
   - **Box Plots:** Illustrating relationships between categorical and numerical variables.

4. **Identifying Patterns and Trends:**
   - **Count and Bar Plots:** Analyzing the relationship between 'Sex' and 'Survived'.
   - **Grouping and Aggregation:** Gaining insights into survival rates by 'Sex'.
   - **Heatmap:** Visualizing the cross-tabulation of 'Sex' and 'Survived'.


## Project Structure
```
├── data/
│   └── Titanic_Dataset.csv                   # Titanic dataset used for analysis and modeling
├── PRODIGY_DS_02.ipynb            # Jupyter Notebook with the entire analysis and modeling process
├── README.md                         # Project description and instructions
└── requirements.txt                  # Python dependencies
```

## Installation
To set up the project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/titanic-dataset-analysis.git
    cd titanic-dataset-analysis
    ```

2. **Create and activate a virtual environment (optional but recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

### Open the Jupyter Notebook:
- Launch Jupyter Notebook and open the `PRODIGY_DS_02.ipynb` file.

### Run the Notebook:
- Execute the cells sequentially to perform data cleaning, exploratory data analysis, model training, and evaluation.
  
### Explore the Analysis:
- The notebook includes detailed comments and markdown cells explaining each step, making it easy to follow the analysis and understand the results.

## Key Sections of the Notebook

- **Importing Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn** for data manipulation, model building, and visualization.
- **Data Cleaning:** Handling missing values and duplicates to prepare the dataset for analysis.
- **Exploratory Data Analysis:** Visualizing data distributions, identifying outliers, and understanding correlations.
- **Exploring Relationships:** Using scatter plots and correlation matrices to explore relationships between variables.
- **Patterns and Trends:** Analyzing the influence of categorical features on survival rates and visualizing these relationships using various plots.

## Results
- **Cleaned Data:** The notebook produces a cleaned version of the Titanic dataset, free of missing values and duplicates.
- **Visualizations:** The notebook includes various visualizations, such as histograms, box plots, pair plots, scatter plots, and heatmaps, to aid in understanding the data.
- **Insights:** The analysis provides insights into the factors that influenced the Titanic's survival, potentially aiding in predictive modeling.

## Conclusion
This analysis thoroughly examines the Titanic dataset, uncovering key patterns and trends that could be valuable for further study or predictive modeling efforts.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
