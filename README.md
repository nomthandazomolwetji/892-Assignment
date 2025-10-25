# 772-892 Agricultural Economics Assignment
## Impact of Merchandise Imports and Sectoral Value Added on Employment

[![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)](https://www.r-project.org/)
[![Quarto](https://img.shields.io/badge/Quarto-75AADB?style=for-the-badge&logo=quarto&logoColor=white)](https://quarto.org/)
[![World Bank Data](https://img.shields.io/badge/Data-World%20Bank-0073e6?style=for-the-badge)](https://databank.worldbank.org/)

## 📋 Overview

This repository contains a comprehensive econometric analysis examining the relationship between international trade, economic structure, and employment outcomes across 50 countries. The study uses World Bank Development Indicators data to investigate how merchandise imports and sectoral value added impact employment patterns.

### 🎯 Research Question
**"What is the impact of merchandise imports and sectoral value added on employment across 50 countries?"**

## 📊 Key Findings

- **Complex Trade-Employment Relationships**: Import intensity effects on unemployment depend significantly on economic structure
- **Sectoral Composition Matters**: Agricultural vs. services orientation moderates trade effects on employment
- **Economic Diversification is Key**: Higher services-to-agriculture ratios associated with lower unemployment
- **Interaction Effects**: Statistical analysis reveals significant interactions between trade intensity and agricultural dependence

## 🗂️ Repository Structure

```
892 Assignment/
├── README.md                     # This file
├── notebooks/
│   ├── Assignment.qmd           # Main analysis (Quarto document)
│   └── Assignment.html          # Rendered HTML output
├── data/
│   ├── raw/
│   │   ├── DATASET A.xlsx       # Population, unemployment, GDP data
│   │   └── DATASET B.xlsx       # Trade and sectoral composition data
│   ├── interim/                 # Intermediate processed data
│   └── processed/               # Final processed datasets
├── reports/                     # Generated reports and outputs
└── 772-892 Assignment 2025.pdf # Assignment instructions
```

## 🚀 Getting Started

### Prerequisites

- **R** (version 4.0 or higher): [Download here](https://cran.r-project.org/)
- **RStudio** (recommended): [Download here](https://posit.co/download/rstudio-desktop/)
- **Quarto** (for rendering): [Download here](https://quarto.org/docs/get-started/)

### Required R Packages

```r
install.packages(c(
  "readxl",      # Excel file reading
  "dplyr",       # Data manipulation
  "tidyr",       # Data reshaping
  "janitor",     # Data cleaning
  "ggplot2",     # Data visualization
  "corrplot",    # Correlation plots
  "gridExtra",   # Plot arrangements
  "scales",      # Plot scaling
  "viridis"      # Color palettes
))
```

### 📖 How to Run the Analysis

1. **Clone the repository**
   ```bash
   git clone https://github.com/nomthandazomolwetji/892-Assignment.git
   cd 892-Assignment
   ```

2. **Open in RStudio**
   - Open `notebooks/Assignment.qmd` in RStudio
   - Set working directory to the project root

3. **Run the analysis**
   - Execute code chunks sequentially using Ctrl+Shift+Enter (Cmd+Shift+Enter on Mac)
   - Or click the green ▶️ arrows in each code chunk

4. **Render the final document**
   ```r
   # In RStudio console
   quarto::quarto_render("notebooks/Assignment.qmd")
   ```

## 📈 Analysis Components

### 1. Data Preparation (10 marks)
- World Bank data import and validation
- Data cleaning and variable standardization
- Dataset joining (50 countries, 6+ economic indicators)

### 2. Variable Engineering (5 marks)
- **Import per capita**: Trade intensity measure
- **Economic diversification ratio**: Services-to-agriculture ratio
- **Labor productivity categories**: Quartile-based classification
- **Employment vulnerability index**: Composite risk measure

### 3. Exploratory Data Analysis (30 marks)
- **4 professional visualizations** using ggplot2
- Trade intensity vs. employment outcomes analysis
- Economic structure and vulnerability relationships
- Correlation matrix heatmaps
- Sectoral composition analysis

### 4. Statistical Analysis (30 marks)
- **Descriptive statistics** by productivity levels
- **Hypothesis testing** (t-tests, correlation tests)
- **Multiple regression models** with interaction effects
- **Logistic regression** for employment vulnerability
- Model diagnostics and validation

### 5. Advanced Modeling (15 marks)
- **Model comparison** using AIC and ANOVA
- **Interaction effects** between trade and sectoral variables
- **Prediction intervals** for policy scenarios
- **Diagnostic plots** and residual analysis

## 📊 Data Sources

- **Primary**: [World Bank Open Data](https://databank.worldbank.org/) - World Development Indicators
- **Coverage**: 50 countries with complete 2023 data
- **Key Indicators**:
  - Population totals
  - Unemployment rates (% of labor force)
  - GDP per person employed
  - Merchandise imports (current USD)
  - Agriculture value added (% of GDP)
  - Services value added (% of GDP)

## 🎓 Academic Context

- **Course**: 772-892 Agricultural Economics
- **Institution**: University assignment
- **Due Date**: October 27, 2025
- **Methodology**: Quantitative econometric analysis
- **Software**: R with tidyverse ecosystem

## 📄 Key Files

- `Assignment.qmd`: Complete analysis with R code, visualizations, and interpretations
- `Assignment.html`: Rendered output for easy viewing
- `DATASET A.xlsx`: Population and employment indicators
- `DATASET B.xlsx`: Trade and sectoral composition data

## 🤝 Contributing

This is an academic assignment, but feedback and suggestions are welcome! Please feel free to:
- Open issues for questions or suggestions
- Fork the repository for your own analysis
- Cite this work if used in academic contexts

## 📜 License

This project is for educational purposes. Data sources retain their original licensing from the World Bank.

## 👤 Author

**[@nomthandazomolwetji](https://github.com/nomthandazomolwetji)**
- Agricultural Economics Student
- Quantitative Analysis Enthusiast
- R Programming & Data Science

---

## 🏆 Assignment Submission

**Status**: Submitted for grading
- ✅ Comprehensive data analysis completed
- ✅ Professional R programming implemented
- ✅ Advanced statistical methods applied
- ✅ Policy-relevant insights developed
- ✅ Detailed code documentation provided

### Key Policy Implications
1. **Differentiated Trade Policies**: Consider sectoral composition in trade liberalization
2. **Economic Diversification**: Promote services sector development
3. **Targeted Interventions**: Focus on high-vulnerability countries identified

---

*This analysis demonstrates rigorous quantitative methods applied to agricultural economics, providing both theoretical insights and practical policy guidance for understanding trade-employment linkages.*
