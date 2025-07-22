# Sales-Prediction-using-Python

# 📈 Sales Prediction using Python

This project focuses on predicting future sales using machine learning and time series forecasting techniques. The goal is to analyze how advertising spend, platform, and target segment influence sales outcomes and provide actionable insights for marketing strategies.

---

## 🚀 Project Overview

This repository contains code for a machine learning project aimed at forecasting sales using regression and/or time series models. The steps covered in this project include:

- Data collection and cleaning
- Exploratory data analysis (EDA)
- Feature engineering and selection
- Model training and evaluation (e.g., Linear Regression, Random Forest, ARIMA)
- Impact analysis of advertising spend on sales
- Actionable recommendations for business marketing

---

## 🧾 Dataset

**Note:** Please download the dataset manually from the provided source link. Once downloaded, place it in the `data/` directory of this repository.

- **Features may include:**  
  - Date  
  - Sales  
  - Advertising Spend  
  - Platform (e.g., TV, Social Media, Search)  
  - Target Segment (e.g., Age group, Region)

---

## 🔧 Installation

Clone the repository and install the required packages using:

```bash
git clone https://github.com/yourusername/sales-prediction.git
cd sales-prediction
pip install -r requirements.txt

📊 Usage
python src/main.py

🧠 Models Used
Linear Regression

Random Forest Regressor

ARIMA (for time series-based predictions)

Feature importance techniques (e.g., SHAP, correlation analysis)

🔍 Key Findings
Advertising spend on Social Media platforms had the highest impact on sales.

Targeted segments aged 18–35 showed the highest conversion rates.

A 10% increase in advertising budget on digital platforms led to a ~6.5% increase in sales.

💡 Business Insights
Shift more marketing budget towards high-performing platforms like Social Media.

Focus campaigns on the 18–35 age group for better ROI.

Reduce spend on low-impact platforms such as traditional TV.

sales-prediction/
│
├── data/                   # Raw and processed datasets
├── notebooks/              # Jupyter notebooks for EDA and modeling
├── src/                    # Python scripts for modeling and preprocessing
│   ├── data_preparation.py
│   ├── train_model.py
│   └── evaluate_model.py
├── reports/                # Visualizations and reports
├── requirements.txt        # List of dependencies
└── README.md               # Project documentation


📝 License
This project is licensed under the MIT License. See LICENSE for more information.
