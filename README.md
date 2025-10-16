# Econometrics Panel Data Project – Impact of COVID-19 on U.S. GDP Growth

This repository contains my final project for *Econ 330: Econometrics* at Pepperdine University.  
The project uses Python to analyze how the spread of COVID-19 affected quarterly GDP growth across U.S. states during 2020–2022.

## 📊 Project Overview
The study constructs a **state–quarter panel dataset** combining:
- **COVID-19 case counts** from the Dartmouth Atlas Project  
- **GDP** from the Bureau of Economic Analysis (BEA)  
- **Unemployment rate** from the Bureau of Labor Statistics (BLS)  
- **Retail sales** from the U.S. Census Bureau  
- **Mobility data** from Google Mobility Reports  
- **Population data** from the U.S. Census Bureau  

## 🧮 Methods
The econometric model uses multiple regression on panel data:

$GDPGrowth_{it} = \beta_1 COVIDCases_{it} + \beta_2 Population_{it} + \beta_3 RetailSales_{it} + \beta_4 Mobility_{it} + \beta_5 UnemploymentRate_{it} + \alpha_i + \lambda_t + \epsilon_{it}$


- Implemented **Pooled OLS**, **Fixed Effects**, and **Random Effects** models  
- Conducted a **Hausman test** to determine the consistent estimator  
- Interpreted and visualized results to assess the effect of COVID-19 on economic performance  

## 🧰 Tools & Libraries
- Python (`pandas`, `numpy`, `statsmodels`, `matplotlib`)
- Jupyter Notebook for analysis and visualization  

## 📈 Key Findings
- A **rise in COVID-19 cases** significantly reduced GDP growth across states.  
- **State fixed effects** controlled for unobserved, time-invariant differences (e.g., local policy and culture).  
- The **fixed effects model** provided the most robust and interpretable results.  

## 📂 Files
- `330Project.ipynb` – full Jupyter notebook with code and regression analysis  
- `Econ330_Final_Paper.pdf` – final report summarizing data, methods, and findings  

## 🧑‍💻 Author
**Cindy Jiang**  
Dual Major: B.S. Mathematics & B.A. Economics, Pepperdine University  
Email: cindy.jiang@pepperdine.edu
