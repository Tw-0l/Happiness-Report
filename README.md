# World Happiness Report Analysis

![Happiness Banner](https://img.shields.io/badge/Happiness-Analysis-brightgreen?style=for-the-badge)

## 🌍 Overview
A comprehensive data analysis project exploring the World Happiness Report dataset to uncover global patterns, correlations, and insights into factors affecting national happiness scores across different countries and regions.

## 🔍 Objectives
This project aims to:
- Analyze key factors contributing to happiness scores worldwide
- Identify regional patterns and differences in happiness metrics
- Explore correlations between economic indicators and well-being
- Visualize trends in happiness scores over time
- Provide actionable insights for policy considerations

## 📊 Key Visualizations & Findings

### Global Happiness Distribution
Visual exploration of happiness scores across different continents, highlighting regional disparities and clusters of similar well-being levels.

### Correlation Analysis
Detailed examination of relationships between happiness scores and factors such as:
- GDP per capita
- Social support
- Healthy life expectancy
- Freedom to make life choices
- Generosity
- Perceptions of corruption

### Trend Analysis
Tracking changes in happiness scores and contributing factors over multiple years, identifying improving and declining regions.

## 🛠️ Technologies & Tools
- **Python**: Primary programming language
- **Pandas & NumPy**: Data manipulation and numerical analysis
- **Matplotlib & Seaborn**: Data visualization
- **Scikit-learn**: Statistical analysis and predictive modeling
- **Jupyter Notebooks**: Interactive development and presentation

## 📁 Repository Structure
```
Happiness-Report/
├── data/                           # Raw and processed datasets
│   ├── world_happiness_report.csv  # Main dataset
│   └── processed/                  # Cleaned and transformed data
├── notebooks/                      # Jupyter notebooks for analysis
│   ├── 01_data_exploration.ipynb   # Initial data exploration
│   ├── 02_correlation_analysis.ipynb
│   └── 03_regional_comparison.ipynb
├── visualizations/                 # Exported charts and figures
├── src/                            # Source code for reusable functions
├── requirements.txt                # Project dependencies
└── README.md                       # Project documentation
```

## 📋 Data Sources
This analysis uses data from the [World Happiness Report](https://worldhappiness.report/), an annual publication of the United Nations Sustainable Development Solutions Network. The report contains survey data on how people evaluate their own lives in various countries around the world.

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- pip package manager

### Installation
1. Clone the repository
   ```bash
   git clone https://github.com/Tw-0l/Happiness-Report.git
   cd Happiness-Report
   ```

2. Create and activate a virtual environment (optional but recommended)
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. Install required dependencies
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook to explore the analysis
   ```bash
   jupyter notebook
   ```

## 💡 Key Insights
- Nordic countries consistently rank among the happiest nations, suggesting their social models contribute significantly to well-being
- GDP shows a strong positive correlation with happiness scores, but with diminishing returns at higher income levels
- Social support emerges as one of the strongest predictors of national happiness
- Regional variations suggest cultural and policy factors play important roles beyond economic indicators

## 🔮 Future Work
- Implement machine learning models to predict happiness scores
- Incorporate additional datasets such as climate data, political stability indices, and health statistics
- Develop an interactive dashboard for exploring the data
- Conduct time-series analysis to better understand evolving trends
- Explore causality through more advanced statistical methods

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request or open an Issue to suggest improvements or additions to the analysis.

## 📞 Contact
- GitHub: [@Tw-0l](https://github.com/Tw-0l)

---

*Understanding what makes societies happier can inform better policy decisions and improve quality of life worldwide. This project aims to contribute to that understanding through data-driven analysis and visualization.*
