# DAX Formulas Used

## 1. Total Revenue
 Total Revenue = SUM(Sales[Revenue])

## 2. Average Order Value  
  Avg Order Value = AVERAGE(Sales[Revenue])

## 3. Revenue by Category
  Revenue by Category = SUMX(Sales, Sales[Quantity] * Sales[Price])

## 4. Customer's Spending
  Customer Spend = DIVIDE([Total Revenue], DISTINCTCOUNT(Sales[Customer_ID]))

