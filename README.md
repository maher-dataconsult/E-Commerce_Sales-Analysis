# E-Commerce 2014~2017 Sales Analysis
  
![Visualization 1](Dashboard.png)


## **Table of Contents**
- [E-Commerce 2014~2017 Sales Analysis](#e-commerce-2014~2017-sales-analysis)
  - [Table of Contents](#table-of-contents)
  - [Collection](#collection)
  - [Cleaning](#cleaning)
  - [Strategic Insights](#strategic-insights)
  - [Recommendations](#recommendations)
  - [Conclusion](#conclusion)
  - [Thank you](#thank-you)

## **Collection**
- Combine all raw data and sheets (4 tables total) into 1 file named **`RAW_Sales_Dataset`**.

---

## **Cleaning**  
1. Removed **1 duplicate row**.  
2. Confirmed **no nulls** in the entire dataset.  
3. Corrected the **`order_date`** datatype.  
4. Transformed **`ship_date`** into 3 columns and merged them into a valid date datatype.  
5. Verified **no outliers** in the following fields:  **`Country`**  & **`State`**  & **`Region`**  & **`Category`**  and **`Subcategory`**  
6. Ensured **`sales`** contains **no zeros or negative numbers**.  
7. Added a calculated column:  
   **`total_revenue = (sales * discount if discount > 0) * quantity`**  
8. Split **country** and **city** using a delimiter.  
9. For **`people`** and **`returns`** tables: Used the first row as header.  
10. Created relationships between tables in **Power Pivot**.  

---

## **Strategic Insights**  
1. **Growth Drivers**:  
   - Accessories and Phones drove category/sub-category dominance.  
   - West region’s efficiency contributed to higher margins.  
2. **Opportunities**:  
   - Expand high-margin categories (Accessories, Technology).  
   - Replicate West’s success in Central/South regions.  
3. **Challenges**:  
   - Inconsistent profit margins outside the West.  
   - Furniture category underperformed despite high sales.  

---

## **Recommendations**  
1. **Optimize Category Mix**:  
   - Prioritize Accessories and Phones in marketing campaigns.  
2. **Regional Strategy**:  
   - Investigate logistics/pricing in Central/South to improve margins.  
3. **Furniture Category Review**:  
   - Analyze cost structures to enhance profitability.  
4. **Data Standardization**:  
   - Clarify regional profit data for deeper insights.  

---

## **Conclusion**  
The dashboard highlights strong growth in 2017, led by Accessories and Phones. Strategic focus on high-margin regions and categories, coupled with operational adjustments for underperformers, can drive sustained growth. 

---

## Thank you 
