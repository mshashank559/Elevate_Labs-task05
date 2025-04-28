 # Indian Army EDA Project

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![Plotly](https://img.shields.io/badge/plotly-5.0%2B-orange)](https://plotly.com/)
[![Seaborn](https://img.shields.io/badge/seaborn-0.11%2B-blueviolet)](https://seaborn.pydata.org/)

## 📖 Overview
This repository presents a comprehensive Exploratory Data Analysis (EDA) of the Global Terrorism Database, with a focus on incidents involving the Indian Army. Leveraging both interactive and static visualizations, the analysis uncovers trends, correlations, and key insights to support data-driven decision-making.

## 🗂️ Table of Contents
1. [Features](#✨-features)
2. [Directory Structure](#🗃️-directory-structure)
3. [Data Access](#📂-data-access)
4. [Installation](#🚀-installation)
5. [Usage](#⚙️-usage)
6. [Key Visualizations](#📊-key-visualizations)
7. [Technologies](#🛠️-technologies)
8. [Project Workflow](#🔄-project-workflow)
9. [License](#📄-license)

## ✨ Features
- **Interactive Plots**: Dynamic charts with Plotly for exploratory insights.
- **Static Exports**: High-resolution PNG exports using Kaleido.
- **Statistical Insights**: Correlation heatmaps and summary statistics with Seaborn.
- **Professional Reporting**: Markdown observations and PDF-export ready notebooks.

## 🗃️ Directory Structure
```
INDIAN_ARMY_EDA/
├── Data/
│   └── Raw Data/
│       └── cleaned_globalterrorism.csv      # Cleaned source data
├── Data-link/
│   └── Link.txt                             # Google Drive link for large datasets
├── notebooks/
│   ├── data_cleaning.ipynb                  # Data preprocessing steps
│   └── eda_indian_army.ipynb                # Main EDA with visualizations
├── output/
│   ├── attack_type_distribution.png         # Pie chart of attack types
│   ├── yearly_attacks.png                   # Yearly attack trend
│   └── ...                                  # Other exported PNGs and HTML files
├── README.md                                # Project overview (this file)
└── requirements.txt                         # Python dependencies

```
## 📂 Data Access
The dataset files (raw and cleaned) are too large to host on GitHub. Download them from Google Drive:
- [Global Terrorism Database - Raw & Cleaned (Drive Link)](https://drive.google.com/drive/folders/1y2qEtO65EPnpX-EVbA7lqJBXV3DxuIei?usp=sharing)


## 🚀 Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/indian-army-eda.git
   cd indian-army-eda
   ```
2. **Create a virtual environment** (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## ⚙️ Usage
> **Note:** Due to an issue with HTML rendering on GitHub, interactive charts embedded in `.html` files may not display correctly. You can view all visualizations as high-resolution PNGs in the `output/` directory or open the HTML files locally in your browser.

1. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook notebooks/eda_indian_army.ipynb
   ```
2. **Run all cells** in sequence:
   - Data import and cleaning
   - Basic exploration (`.info()`, `.describe()`, `.value_counts()`)
   - Interactive Plotly visualizations
   - Seaborn heatmap & histograms
   - Save plots to `output/`
   - Add markdown observations
3. **Export to PDF** for final reporting via Jupyter’s **File → Export Notebook As → PDF**.

## 📊 Key Visualizations
- **Attack Type Distribution**: Pie chart displaying proportions of attack types.
- **Yearly Attack Trends**: Line chart tracking annual attack counts.
- **Top 10 Countries**: Bar chart of countries with the highest incidents.
- **Country vs Attack Type Heatmap**: Visual correlation between countries and attack methods.
- **Number of Kills Distribution**: Interactive histogram with box-plot marginal.
- **Correlation Heatmap**: Seaborn heatmap of numerical feature relationships.

## 🛠️ Technologies
- **Python 3.8+**
- **Pandas & NumPy**: Data manipulation
- **Plotly & Kaleido**: Interactive and static charting
- **Seaborn & Matplotlib**: Statistical plotting
- **Jupyter Notebook**: Interactive development environment
- **VS Code**: Code editor

## 🔄 Project Workflow
1. **Data Cleaning** (`data_cleaning.ipynb`): Handle missing values, type conversions.
2. **Exploratory Analysis** (`eda_indian_army.ipynb`): Generate insights via visualizations and statistics.
3. **Export Visuals**: Save high-quality PNGs to `output/`.
4. **Reporting**: Compile findings into a PDF report.



## 📄 License
This project is licensed under the [MIT License](LICENSE).

---
*Prepared by Shashank Mishra, Date: 2025-04-28*



