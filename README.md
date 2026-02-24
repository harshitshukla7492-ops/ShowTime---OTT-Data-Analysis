# Austo - DataAnalytics
## 📋 Project Overview

This project performs a comprehensive **Exploratory Data Analysis (EDA)** and statistical analysis on automobile purchase data to uncover patterns, relationships, and insights about customer demographics, financial profiles, and vehicle preferences. The analysis leverages customer information including age, salary, education, marital status, and automobile preferences to answer critical business questions about purchasing behavior.

## 🎯 Project Objectives

This data analysis project aims to:

1. **Clean and Preprocess Data** - Handle missing values, treat outliers, and validate data integrity
2. **Explore Data Distributions** - Analyze demographic and financial patterns across the customer base
3. **Identify Relationships** - Discover correlations between customer attributes and purchasing behavior
4. **Answer Business Questions** - Provide data-driven insights on:
   - Gender preferences for vehicle types (SUVs vs Sedans)
   - Likelihood of salaried individuals purchasing specific vehicles
   - Average spending patterns across demographics
   - Impact of financial status (personal loans, house loans) on purchases
   - Influence of household income (working partners) on vehicle selection

## 📊 Dataset Overview

The analysis uses an automobile customer dataset containing **customer demographics, financial information, and vehicle preferences**.

### Key Variables:
- **Demographic:** Age, Gender, Marital Status, Education, Profession
- **Financial:** Salary, Partner Salary, Total Household Salary, Personal Loan, House Loan
- **Vehicle Info:** Car Make/Type (SUV, Sedan), Price, Number of Dependents
- **Household:** Partner Employment Status

## 🔧 Methodology

### 1. **Data Cleaning & Preprocessing**
   - Identified and handled missing values using mode (categorical) and median (numerical) imputation
   - Detected and treated data irregularities (e.g., negative salary values)
   - Validated data completeness after treatment

### 2. **Exploratory Data Analysis (EDA)**
   - Generated distribution plots for all categorical and numerical variables
   - Created visualizations including histograms, box plots, count plots, and bar charts
   - Calculated summary statistics and identified key patterns

### 3. **Outlier Treatment**
   - Applied IQR (Interquartile Range) method to detect outliers
   - Capped outliers to 5th and 95th percentiles to preserve data while reducing extreme values
   - Verified outlier treatment through post-treatment visualization

### 4. **Correlation & Relationship Analysis**
   - Computed correlation matrix for numerical variables
   - Created correlation heatmaps to visualize relationships
   - Generated pair plots to explore variable relationships
   - Analyzed categorical vs numerical variable interactions using box plots and bar plots

### 5. **Business Insights Analysis**
   - Cross-tabulation analysis (e.g., Gender vs Car Make preferences)
   - Contingency table analysis for categorical relationships
   - Calculated proportions and percentages for specific customer segments

## 📈 Key Findings

### Gender & Vehicle Preferences
- Men and women show distinct preferences for vehicle types
- Significant variation in SUV vs Sedan purchasing patterns by gender

### Salaried Male Purchasing Patterns
- Data reveals measurable preferences for SUV purchases among salaried males
- Provides evidence-based insights on targeting strategies

### Financial Impact on Purchases
- Average car price varies significantly by gender
- Household financial status (dual income, partner employment) strongly influences vehicle purchase prices
- Customers with working partners tend to purchase higher-priced vehicles

### Loan Impact
- Personal loan status affects total spending on vehicles
- House loan holders show distinct purchasing patterns

### Age & Salary Relationships
- Strong correlation between age and salary levels
- Clear patterns in customer age distribution (majority 25-45 age range)

## 🛠️ Technologies Used

- **Python 3.x** - Primary programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Jupyter Notebook** - Interactive analysis environment

## 📁 Project Structure

```
ShowTime---OTT-Data-Analysis/
├── PDS Project.ipynb          # Main analysis notebook
├── README.md                   # This file
└── Data/
    └── austo_automobile.csv    # Dataset
```

## 🚀 How to Use

1. **Install Dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

2. **Run Analysis:**
   - Open `PDS Project.ipynb` in Jupyter Notebook
   - Execute cells sequentially to run the complete analysis

3. **View Results:**
   - Generated visualizations appear in the notebook
   - Statistical summaries and insights are printed to output

## 💡 Key Insights for Business

- **Marketing Strategy:** Tailor vehicle recommendations based on gender and financial profiles
- **Sales Targeting:** Focus SUV sales on salaried males with higher income potential
- **Product Strategy:** Offer higher-priced vehicles to dual-income households
- **Loan Integration:** Coordinate personal loan offerings with vehicle purchase campaigns
- **Demographic Focus:** Target prime customer segment (25-45 age range, graduates, married)

## 📌 Notes

- Missing values were intelligently filled based on data type (mode for categorical, median for numerical)
- Outlier treatment preserves data integrity while reducing impact of extreme values
- Analysis includes both univariate and multivariate statistical approaches
- All visualizations generated for comprehensive pattern recognition

---

*Last Updated: February 2026* 

