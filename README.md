# Cleaning and Exploring eBay Car Sales Data

This project involves cleaning and exploring used car sales data that originated from eBay-Kleinanzeigen (a German classifieds site).  
The main goal was to perform data cleaning, and identify **pricing patterns, brand trends, and mileage behaviors** that can help potential buyers or sellers make data-driven decisions in the automotive market.

---

##  Objectives
- Clean and prepare raw car listing data for analysis.  
- Explore trends and relationships between variables (e.g., price vs. mileage, brand vs. price).  
- Identify outliers and unrealistic listings.  
- Derive insights into the most cost-efficient brands and models.  
- Visualize data to highlight key pricing trends.
  
---

## Dataset Information
**Source:** eBay Kleinanzeigen Used Car Listings Dataset via Dataquest
(German used car marketplace — eBay Kleinanzeigen)

**Description:**
The dataset contains information on used car listings, including:
- Price
- Brand
- Vehicle type
- Registration year
- Power (PS)
- Mileage (km)
- Date listed

---

## Key Steps Performed
- Removed inaccurate and unrealistic values
- Converted data types (e.g., numeric columns stored as text)
- Normalized column names
- Filtered data to realistic price & mileage ranges
- Performed exploratory data analysis (EDA)

---

## Key Insights
- Volkswagen is the most frequently listed brand even though its average price sits around the mid-range; strongest market share.
- Premium German brands (BMW, Mercedes, Audi) have significantly higher average prices, but not significantly lower mileage; pricing is driven more by brand equity than remaining vehicle life.
- Budget brands (Ford, Opel) have lower average prices and similar mileage ranges → good value for buyers with tighter budgets.
- Mileage variation across top brands is relatively narrow (≈ within ±10%); mileage is not the primary driver of price in this dataset.
- Volkswagen balances value and demand 
- Audi is the priciest on average (in this dataset), positioning it at the top of the premium segment.

---

## Recommendations
- Buyers looking for the best balance between price and reliability perception should consider **Volkswagen**.
- Premium buyers prioritizing luxury experience and brand prestige can target **BMW / Mercedes / Audi**, but should not expect better mileage for the higher price.
- Price-sensitive buyers can choose **Ford or Opel** for good affordability without a major sacrifice in typical mileage.
- Used-car buyers should not assume **“high price = low mileage”**; instead they should compare **specific car history** (service records, accident history, previous owners) not just brand label.

---

## Tools & Technologies Used
- **Python**  
- **Pandas** for data cleaning and manipulation  
- **NumPy** for numerical operations  
- **Jupyter Notebook** for exploration and presentation

---

## Files
**Analyis Notebook;** [Jupyter Notebook: Data Cleaning & EDA](eBay_car_sales_cleaning_eda.ipynb)

**CSV File:** [Ebay Dataset](autos.csv)

---

## How to Use

### 1. Clone the Repository
```bash
git clone https://github.com/linetrono/Used-Car-Pricing-Analysis-Python_Project.git
cd Used-Car-Pricing-Analysis-Python_Project
```

### 2. Install Dependencies
Ensure you have Python 3 installed, then install required libraries: Numpy & Pandas
```bash
pip install pandas numpy 
```

### 3. Run the Notebook
```bash
jupyter notebook notebooks/ebay_car_sales_cleaning_eda.ipynb
```

## Contact
For questions, collaboration, or feedback, feel free to reach out:

[Email:](mukamihrono@gmail.com)

[LinkedIn:](https://www.linkedin.com/in/linet-rono-b32130277/)

[GitHub:](https://github.com/linetrono)
