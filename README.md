### Introduction

This notebook presents an exploratory analysis of a dataset of sales from an online store that operates nationwide. The aim of the analysis is to identify the best-selling departments, understand the price behavior by department, analyze the seasonality of sales, the average income by sales channel and the age range of customers.

### Methodology

The analysis was carried out using the Pandas Python library in the Google Colab environment. The stages of the analysis were as follows:

1. **Data Import and Pre-processing:**
    * The dataset was imported and loaded into a Pandas DataFrame.
    * The business assumptions were considered and applied to the data, such as:
        * Filling in the UF with Mato Grosso do Sul for purchases without this information.
        * Exclusion of sales with a final price higher than the price with freight.
        * Imputing the price of the product with the price with freight for products without a price.
        * Elimination of the 'TV_and_Video' department and incorporation into the 'TVs_and_Accessories' department.
        * Deletion of the 'APP' category and incorporation into the 'Application' category.
2. **Exploratory Analysis
    * Top-selling departments:**
        * The frequency of sales by department was calculated.
        * The departments with the highest sales frequency were identified.
    **Average price with freight per department:**
        * The average freight price per department was calculated.
        * The departments with the highest and lowest average prices have been identified.
    * Quantity of sales per month:**
        * The number of sales per month was calculated.
        * The months with the highest and lowest sales were identified.
        * The existence of seasonality in sales was checked.
    * Average income per sales channel:**
        * The average income per sales channel was calculated.
        * The sales channels with the highest and lowest average income were identified.
    **Average age of customers by banner:**
        * The average age of customers by banner was calculated.
        * The banners with the highest and lowest average customer age were identified.

### Results

* The best-selling departments were: Fashion, Furniture and Electronics.
* The department with the highest average price was Electrical Appliances and the lowest was Beverages.
* A seasonality in sales was observed, with a greater number of sales in the months of November and December.
* The sales channel with the highest average income was Credit Card and the lowest was Boleto Bancário.
* The flag with the highest average age of customers was Blue and the lowest was Green.

### Conclusion

The exploratory analysis of the online store's sales data made it possible to identify valuable information about customer behavior and sales characteristics. This information can be used to:

* Adjust the product purchasing strategy, prioritizing departments with greater profitability and demand.
* Implement marketing actions aimed at different target audiences, taking into account the preferred age group and sales channel.
* Optimize product pricing, taking into account the average price per department and the desired profit margin.
* Plan specific marketing campaigns for each period of the year, according to the seasonality of sales.

### Next steps

It is advisable to carry out more in-depth analysis to confirm the results of the exploratory analysis and identify new business opportunities. Some suggestions for future analysis:

* Customer segmentation analysis to identify groups of customers with similar characteristics and behaviors.
* Churn analysis to identify the reasons why customers stop buying from the store.
* Lifetime value analysis to identify the most profitable customers for the store.

### Remarks

* This notebook is just an example of exploratory data analysis. It is important that the analysis is adapted to the specific context of each business.
* The results of the analysis may vary according to the quality of the data used.

**To find out more

* Connect with me on [LinkedIn](https://www.linkedin.com/in/daniel-braga-reis-725aa012a/)
* Explore my projects on [GitHub](https://github.com/Danielbrgs?tab=repositories)
