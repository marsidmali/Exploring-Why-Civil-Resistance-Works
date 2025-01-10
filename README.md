# 📊 Exploring Why Civil Resistance Works

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A statistical analysis replicating key findings from "Why Civil Resistance Works" by Erica Chenoweth and Maria J. Stephan, investigating the effectiveness of nonviolent versus violent campaigns.

## ✨ Features

1. **Historical Trends Analysis**
   - Frequency analysis of nonviolent vs violent campaigns by decade
   - Success rate comparison between campaign types
   - Visualization of campaign trends over time

2. **Participation Analysis**
   - Investigation of the 3.5% rule
   - Analysis of largest resistance campaigns (1946-2014)
   - Statistical validation of participation thresholds

3. **Statistical Modeling**
   - Logistic regression analysis of campaign success factors
   - Control for population size and regime type
   - Confidence interval analysis for success probability


## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/marsidmali/Exploring-Why-Civil-Resistance-Works.git
cd Exploring-Why-Civil-Resistance-Works
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## 📁 Project Structure

```plaintext
Exploring-Why-Civil-Resistance-Works/
│
├── data/                # Dataset files
│   ├── NAVCO 1.2 Updated.xlsx
│   └── p5v2018.xls
│
├── notebooks/          # Jupyter notebooks
│   └── Exploring-Why-Civil-Resistance-Works.ipynb
│
├── requirements.txt    # Dependencies
└── README.md          # Documentation
```

## 🚀 Usage

1. Launch Jupyter Notebook:
```bash
jupyter notebook
```

2. Open `Exploring-Why-Civil-Resistance-Works.ipynb`
3. Run all cells to perform the analysis

## 📊 Data Sources

- [NAVCO 1.2 Dataset](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/0UZOTX)
- [Polity5 Annual Time-Series](http://www.systemicpeace.org/inscr/p5v2018.xls)

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
