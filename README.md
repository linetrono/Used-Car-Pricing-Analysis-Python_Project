# Cleaning and Exploring eBay Car Sales Data

This project involves cleaning and exploring used car sales data that originated from eBay-Kleinanzeigen (a German classifieds site).  
The main goal was to wrangle messy real-world data, perform data cleaning, and generate insights into brand pricing and mileage behavior.

---

### Key Steps Performed
- Removed inaccurate and unrealistic values
- Converted data types (e.g., numeric columns stored as text)
- Normalized column names
- Filtered data to realistic price & mileage ranges
- Performed exploratory data analysis (EDA)

---

### Insights

- Volkswagen is the most frequently listed brand even though its average price sits around the mid-range; strongest market share.
- Premium German brands (BMW, Mercedes, Audi) have significantly higher average prices, but not significantly lower mileage; pricing is driven more by brand equity than remaining vehicle life.
- Budget brands (Ford, Opel) have lower average prices and similar mileage ranges → good value for buyers with tighter budgets.
- Mileage variation across top brands is relatively narrow (≈ within ±10%); mileage is not the primary driver of price in this dataset.
- Volkswagen balances value and demand 
- Audi is the priciest on average (in this dataset), positioning it at the top of the premium segment.

---

### Recommendations

- Buyers looking for the best balance between price and reliability perception should consider **Volkswagen**.
- Premium buyers prioritizing luxury experience and brand prestige can target **BMW / Mercedes / Audi**, but should not expect better mileage for the higher price.
- Price-sensitive buyers can choose **Ford or Opel** for good affordability without a major sacrifice in typical mileage.
- Used-car buyers should not assume **“high price = low mileage”**; instead they should compare **specific car history** (service records, accident history, previous owners) — not just brand label.

---

### Tools & Technologies Used
- Python
- Pandas
- Jupyter Notebook
- NumPy

---

### Files
[Jupyter Notebook: Data Cleaning & EDA](eBay_car_ sales_cleaning_eda.ipynb)

[Ebay Dataset](autos.csv)


