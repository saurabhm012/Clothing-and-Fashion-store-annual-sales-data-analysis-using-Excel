# Clothing-and-Fashion-store-annual-sales-data-analysis-using-Excel

### Objective: 
To create an in-depth annual sales report for 2022 that analyzes online sales data from multiple platforms, providing actionable insights for the clothing and fashion store to optimize its sales strategy and share insights to find the most suitable customer base for the store to target.

### Data Description:
1. index: A unique identifier for each record in the dataset.
2. Order ID: A unique identifier for each order placed.
3. Cust ID: A unique identifier for each customer.
4. Gender: The gender of the customer, indicating whether the customer is male or female.
5. Age: The age of the customer.
6. Date: The date on which the order was placed.
7. Status: The current status of the order (e.g., Delivered, Pending, Cancelled).
8. Channel: The platform through which the order was placed (e.g., Myntra, Ajio, Amazon).
9. SKU: The Stock Keeping Unit, a unique identifier for each product.
10. Category: The category of the product (e.g., kurta, set).
11. Size: The size of the product ordered.
12. Qty: The quantity of the product ordered.
13. currency: The currency in which the transaction was made (e.g., INR for Indian Rupee).
14. Amount: The total amount paid for the order.
15. ship-city: The city to which the order was shipped.
16. ship-state: The state to which the order was shipped.
17. ship-postal-code: The postal code of the shipping address.
18. ship-country: The country to which the order was shipped.
19. B2B: A boolean value indicating whether the order was a Business-to-Business (B2B) transaction (True) or a Business-to-Consumer (B2C) transaction (False).

#### Derived Fields (Highlighted in the dataset):
* Age Group: Derived from age("Senior" >= 50, "Adult" >= 30, "Teenager"(Rest)).
* Month: Extracted from Date.

### Data Cleaning (Steps Taken):
* Identifying Inconsistencies: Applied filters on all columns to check for distinct values and identify any inconsistencies or errors.
* Gender Column: Found inconsistencies in the gender column where male was written as both "M" and "Male" and similarly for female. Filtered out all the "M" values and replaced them with "Men", and replaced all "W" values with "Women". This standardization resulted in only two distinct values in the gender column: "Men" and "Women".
* Quantity Column: Identified inconsistencies where the quantity data was represented both numerically and textually (e.g., "one" vs. "1"). Replaced all textual data with the corresponding numeric values to ensure consistency across the column.

### Data Analysis Summary:
* We analyzed monthly sales and orders using pivot tables and visualized the trends with a combo chart. Gender-wise sales were examined and represented in a pie chart. Order statuses were categorized into delivered, refunded, returned, and canceled, and displayed in another pie chart. State-wise sales were analyzed, highlighting the top 5 states in a bar chart. Lastly, we examined order counts by age group and gender, visualized through a column chart.

### Insights & Final Conclusion:
* Women are more likely to buy compared to men (~65%).
* Maharashtra, Karnataka and Uttar Pradesh are the top 3 states (~35%).
* Adult age group (30-49 yrs) is max contributing (~50%).
* Amazon, Flipkart and Myntra channels are max contributing (~80%).
* Target women customers of age group (30-49 yrs) living in Maharashtra, Karnataka and Uttar Pradesh by showing ads/offers/coupons available on Amazon, Flipkart and Myntra
Activate Windows.
