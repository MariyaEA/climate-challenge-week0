# Climate Challenge Week 0

## Project Overview

This project analyzes historical climate and weather data from five African countries: Ethiopia, Kenya, Sudan, Tanzania, and Nigeria.

The goal is to identify climate trends, seasonal patterns, anomalies, and vulnerability signals that can support evidence-based climate policy discussions ahead of COP32.

---

## Business Context

EthioClimate Analytics has been engaged to support Ethiopia's preparations for COP32 by producing clear, evidence-backed insights from historical climate data.

The analysis focuses on three key questions:

1. What is changing in the climate data?
2. What risks or impacts could these changes suggest?
3. What policy or adaptation actions could the evidence support?

---

## Analytical Framework

This project follows a three-layer analytical approach:

1. **Data Layer** — Cleaning and structuring raw climate data  
2. **Analysis Layer** — Identifying trends, patterns, and relationships  
3. **Insight Layer** — Translating findings into real-world implications and decision support  

This framework ensures the analysis moves beyond exploration into actionable insights.

---

## Multi-Country Analysis

The analysis is conducted across five countries:

- Ethiopia  
- Kenya  
- Nigeria  
- Tanzania  
- Sudan  

Each country is analyzed individually using a consistent methodology, followed by a comparative analysis to identify regional patterns, similarities, and differences in climate behavior.

---

## Key Outputs

- Exploratory Data Analysis (EDA) for each country  
- Temperature trend analysis  
- Rainfall distribution and seasonality  
- Correlation analysis of climate variables  
- Cross-country comparison of climate patterns  

---

## Key Insights

- Rainfall is highly seasonal across countries, with peaks between June and September  
- Most days experience low precipitation, with occasional extreme rainfall events  
- Temperature shows a gradual upward trend across multiple countries  
- Temperature and humidity exhibit an inverse relationship  
- Climate variability suggests potential risks for agriculture and water systems  

---

## Notebooks

- `ethiopia_eda.ipynb` — Detailed analysis for Ethiopia  
- `kenya_eda.ipynb` — Analysis for Kenya  
- `nigeria_eda.ipynb` — Analysis for Nigeria  
- `tanzania_eda.ipynb` — Analysis for Tanzania  
- `sudan_eda.ipynb` — Analysis for Sudan  

---

## Repository Structure

```text
climate-challenge-week0/
├── .github/workflows/   # CI workflow
├── data/                # Local data files, ignored by Git
├── notebooks/           # Exploratory analysis notebooks
├── scripts/             # Helper scripts
├── src/                 # Reusable source code
├── tests/               # Test files
├── README.md
├── requirements.txt
└── .gitignore


## Setup Instructions

1. Clone the repository:
git clone https://github.com/YOUR-USERNAME/climate-challenge-week0.git
cd climate-challenge-week0

2. Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate   # Mac/Linux

3. Install dependencies:
pip install -r requirements.txt

4. Run the notebooks:
jupyter notebook