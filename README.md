# Billionaires Analysis with Python

This project analyzes billionaires around the world using the Forbes 2021 Billionaires dataset. The analysis provides insights about countries, industries, sources of wealth, and age groups through data visualization and exploration.

---

## Dataset Columns

- **Name**: Full name of the billionaire  
- **NetWorth**: Net worth of the billionaire (in USD)  
- **Country**: Country of residence or citizenship  
- **Source**: Source of wealth (e.g., Technology, Fashion, Finance)  
- **Rank**: Forbes ranking of the billionaire  
- **Age**: Age of the billionaire  
- **Industry**: Industry in which the billionaire operates  

---

## Data Visualization Summary

- **Country distribution:** The United States, China, and India have the highest number of billionaires.  
- **Industry distribution:** Technology and Fashion/Retail sectors have the most billionaires.  
- **Source of wealth:** Most wealth comes from technology and investments.  
- **Age groups:** The 50-70 age group has the highest number of billionaires.  
- **Wealth distribution (Boxplot):** Some countries have extreme outliers, especially the US and China.  
- **Numeric relationships (Pairplot):** NetWorth, Rank, and Age show clear patterns; younger billionaires generally have lower net worth, while top-ranked billionaires tend to be older and wealthier.

---

## How to Use

1. Load the dataset: `df = pd.read_csv('billionaires.csv')`  
2. Check and clean missing values (especially in the `Age` column)  
3. Convert numeric and categorical columns to the appropriate format  
4. Visualize data using Countplot, Boxplot, Pie Chart, and Pairplot  
5. Save plots as `.png` or `.jpg` files for reports or presentations  

---

## Libraries Required

- pandas  
- numpy  
- matplotlib  
- seaborn  

---

## Conclusion

This analysis visualizes the distribution of billionaires worldwide, their wealth, and industry concentration. It provides key insights and serves as an example for data analysis and visualization projects.
