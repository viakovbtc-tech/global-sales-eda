# Global Sales EDA

End-to-end Exploratory Data Analysis of a global retail company operating across online and offline sales channels.

---

## Key Findings

- Europe generates **94.2% of total revenue** and **94.7% of total profit**, indicating extremely high geographic concentration.
- Core profit-driving categories: Office Supplies, Household, Cosmetics.
- Online and offline channels contribute almost equally, confirming a balanced multi-channel model.
- Median shipping time is approximately 25 days with a right-skewed distribution and long-tail delays.
- No strong negative relationship between delivery speed and profit was identified.
- Geographic diversification represents a key long-term growth opportunity.

---

## Project Overview

This project presents an end-to-end Exploratory Data Analysis (EDA) of a global retail company operating both online and offline sales channels.

The objective was to clean, transform, merge, and analyze transactional, product, and geographic data in order to extract business insights and identify growth opportunities.

---

## Dataset

The analysis is based on three datasets:

- `events.csv` — transactional sales data  
- `products.csv` — product categories and product IDs  
- `countries.csv` — country codes, regions, and sub-regions  

### Key relationships

- `Product ID` connects events to products  
- `Country Code (alpha-3)` connects events to countries  

---

## Data Preparation

The project includes:

- Missing value handling  
- Type conversion (dates, numeric fields)  
- Duplicate detection and text normalization  
- Logical consistency checks  
- Feature engineering:
  - Revenue  
  - Profit  
  - Shipping delay  
  - Time-based features (month, weekday)  

---

## Key Business Questions

- Which product categories generate the highest revenue and profit?
- Which regions and countries drive performance?
- Is there monthly or weekly seasonality?
- Does shipping delay affect profitability?
- How do online and offline channels compare?

---

## Detailed Insights

- Europe is the dominant revenue-generating region.
- Office Supplies and Household categories form the financial core of the business.
- Sales demonstrate clear monthly and weekly seasonality.
- Shipping delay varies significantly by country.
- No strong direct relationship between delivery speed and profit was identified.
- Online and offline channels contribute almost equally.

---

## Business Conclusion

The company operates a stable multi-channel model driven by high-performing product categories and strong European concentration.

While operationally stable, the current structure presents geographic concentration risk.

Strategic growth opportunities include:

- Geographic diversification beyond Europe  
- Scaling high-margin categories  
- Targeted logistics optimization in delay-heavy countries  

---

## Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly  
- Google Colab  

---

## How to Run

Install dependencies:

pip install -r requirements.txt

Open `Global_Sales_EDA.ipynb` in Jupyter Notebook or Google Colab.

Make sure dataset files are available locally or update file paths accordingly.
