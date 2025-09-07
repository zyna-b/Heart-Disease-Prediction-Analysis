# 🫀 Heart Disease Prediction Analysis | Complete EDA & Statistical Testing

[![Python](https://img.shields.io/badge/Python-3.9-blue.svg)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)](https://pandas.pydata.org)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-yellow.svg)](https://scikit-learn.org)

> **Comprehensive Exploratory Data Analysis (EDA) and Statistical Feature Selection for Heart Disease Prediction using Machine Learning**

## 📊 Project Overview

This project performs an in-depth **heart disease analysis** using statistical methods and machine learning techniques. The analysis includes comprehensive **exploratory data analysis (EDA)**, **feature engineering**, **statistical hypothesis testing**, and **data preprocessing** for predictive modeling.

### 🎯 Key Features

- ✅ **Complete EDA Pipeline** - Data exploration, visualization, and insights
- ✅ **Statistical Feature Selection** - T-tests and Chi-square tests with Cramer's V
- ✅ **Data Cleaning & Preprocessing** - Missing value imputation and encoding
- ✅ **Advanced Visualizations** - Correlation heatmaps, distribution plots, and categorical analysis
- ✅ **Feature Engineering** - One-hot encoding and standardization
- ✅ **Ready for ML Models** - Preprocessed dataset for machine learning

## 📁 Dataset Information

**Dataset**: Heart Disease Prediction Dataset  
**Source**: Clinical heart disease data  
**Size**: 918 patients with 12 features  
**Target**: Heart Disease (Binary classification: 0 = No Disease, 1 = Disease)

### 📋 Features Analyzed

| Feature | Type | Description |
|---------|------|-------------|
| **Age** | Continuous | Patient age in years |
| **Sex** | Categorical | Gender (M/F) |
| **ChestPainType** | Categorical | Type of chest pain (ATA, NAP, ASY, TA) |
| **RestingBP** | Continuous | Resting blood pressure |
| **Cholesterol** | Continuous | Serum cholesterol levels |
| **FastingBS** | Binary | Fasting blood sugar > 120 mg/dl |
| **RestingECG** | Categorical | Resting electrocardiogram results |
| **MaxHR** | Continuous | Maximum heart rate achieved |
| **ExerciseAngina** | Binary | Exercise-induced angina |
| **Oldpeak** | Continuous | ST depression induced by exercise |
| **ST_Slope** | Categorical | Slope of peak exercise ST segment |

## 🔬 Analysis Methodology

### 1. **Exploratory Data Analysis (EDA)**
- Data structure and quality assessment
- Missing value analysis and treatment
- Distribution analysis of continuous variables
- Categorical variable frequency analysis
- Target variable distribution and balance

### 2. **Data Visualization**
- **Histograms** with KDE for continuous variables
- **Count plots** for categorical variables vs target
- **Box plots** and **violin plots** for distribution comparison
- **Correlation heatmap** for feature relationships

### 3. **Statistical Feature Selection**
- **T-tests** for continuous variables (with Cohen's d effect size)
- **Chi-square tests** for categorical variables (with Cramer's V)
- **P-value analysis** for statistical significance (α = 0.05)
- **Effect size interpretation** for practical significance

### 4. **Data Preprocessing**
- **Missing value imputation** (mean imputation for continuous variables)
- **One-hot encoding** for categorical variables
- **Feature standardization** using StandardScaler
- **Feature selection** based on statistical significance

## 📈 Key Findings & Results

### 🎯 Statistically Significant Features
Based on comprehensive statistical testing (p < 0.05):

**Continuous Variables (T-test results):**
- Age ✅
- Maximum Heart Rate ✅
- Oldpeak (ST Depression) ✅
- Chest Pain Type ✅
- Exercise Angina ✅

**Categorical Variables (Chi-square results):**
- Sex ✅
- ST_Slope ✅
- Resting ECG ✅

### 📊 Model-Ready Dataset
- **Original Features**: 16 (after encoding)
- **Selected Features**: X significant features
- **Data Split**: Ready for train/test split
- **Preprocessing**: Standardized and encoded

## 🛠️ Technical Stack

| Technology | Purpose |
|------------|---------|
| **Python 3.9** | Programming language |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical computing |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical data visualization |
| **SciPy** | Statistical testing |
| **Scikit-learn** | Machine learning and preprocessing |
| **Jupyter Notebook** | Interactive development environment |

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.9+
Jupyter Notebook
```

### Installation
1. **Clone the repository**
```bash
git clone https://github.com/your-username/heart-disease-analysis.git
cd heart-disease-analysis
```

2. **Create virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter
```

4. **Run the analysis**
```bash
jupyter notebook heart_disease_analysis.ipynb
```

## 📝 Usage

1. **Open the Jupyter notebook**
2. **Run cells sequentially** for complete analysis
3. **Review EDA insights** in visualization sections
4. **Examine statistical test results** for feature importance
5. **Use the final preprocessed dataset** for machine learning models

## 📊 File Structure

```
heart-disease-analysis/
│
├── heart_disease_analysis.ipynb    # Main analysis notebook
├── heart.csv
├── README.md                       # Project documentation
└── venv_py39/                      # Virtual environment
```

## 🔍 Statistical Analysis Details

### Hypothesis Testing
- **Null Hypothesis (H₀)**: No significant difference between groups
- **Alternative Hypothesis (H₁)**: Significant difference exists
- **Significance Level**: α = 0.05
- **Effect Size Metrics**: Cohen's d for continuous, Cramer's V for categorical

### Feature Selection Criteria
- **P-value < 0.05** for statistical significance
- **Effect size consideration** for practical importance
- **Clinical relevance** for medical interpretation

## 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🏷️ Keywords

`heart disease prediction` `medical data analysis` `exploratory data analysis` `statistical testing` `feature selection` `machine learning` `healthcare analytics` `python data science` `medical AI` `cardiovascular analysis` `clinical data mining` `predictive healthcare`

## 📧 Contact

**Author**: Zainab Hamid  
**Email**: zainabhamid2468@gmail.com 
**LinkedIn**: [Your LinkedIn Profile](https://www.linkedin.com/in/zainab-hamid-187a18321/)  
**GitHub**: [Your GitHub Profile](https://github.com/zyna-b)

---

⭐ **Star this repository** if you found it helpful!

🔗 **Share** with others interested in medical data analysis and machine learning!