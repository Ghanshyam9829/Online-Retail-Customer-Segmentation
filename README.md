# Online-Retail-Customer-Segmentation
Capstone Project-4-Online-Retail-Customer-Segmentation


**Project Summary -**

In the project a unique data set given which is from a company who sell gift items ,Given data set is having 541909 Rows and 8 Columns , columns are explianed as below :-

1.InvoiceNo contains unique bill number given data in the form of object data type
2.StockCode contains a unique stock/gift code given data in the form of object data type
3.Description contains a brief description of gift items given data in the form of object data type
4.Quantity contains the total number of gift items quantity given data in the form of int data type
5.InvoiceDate contains the date of purchase given data in the form of datetime data type
6.UnitPrice contains gift price per item given data in the form of float data type
7.CustomerID contains customer id given data in the form of float data type
8.Country contains the respective country name belonging to the customer

After Uplloading the data set in the colab we do some analysis which is explained in the below points :-

1.Load the data

2.First View of the data by using Head function

3.Exploratory data analysis

4.Hypothesis Testing

5.Feature Engineering & Data Pre-processing (missing values, prepare data for modeling, and handled outliers and data scaling)

6.data modeling here we have formed clusters using Kmeans cluster and silhouette analysis and finally, we have visualized all clusters using dendrograms.

Above steps are used for the Online Retail Customer Segmentation unsupervised capstone project.

Insights from the project

1WHITE HANGING HEART T-LIGHT HOLDER is most in demand.

2.United Kingdom is the country who is buying most number of gifts.

3.Saudi Arabia bought least number of gifts.

4.DOTCOM POSTAGE is the gift which genrated the highest revenue

5.Invoice no 5881483 is having highest quantity which is 80995

6.invoice NO 581483 has a final sell of 168469 .

7.DOT stock code gift generated a total of $ 2,06,245 in revenue .

8.WORLD WAR 2 GLIDERS is the most bought item ever with 53847 quantity.

9.Total reveanue of only UK is 8 million.

***Problem Statement***

In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.


***Variables Description***

Fields : Description

Invoice NO : Invoice number

Stock Code : Stock name code

Description : Description of product

Quantity : Quantity bought

InvoiceDate : Invoice date

UnitPrice : Price per unit

Customer ID : Unique customer id

Country : location

***Hypothesis Testing***

Based on your chart experiments, define three hypothetical statements from the dataset. In the next three questions, perform hypothesis testing to obtain final conclusion about the statements through your code and statistical testing.

1.Is 5$ price for each gift product?

2.Is 10 quantity of gift buying across UK region?

3.Consider the final sales is 15

**Conclusion**

Product Strategy: The analysis of the pie chart and top purchased items guides the online store in refining its product strategy. Recognizing the popularity of items like the "White Hanging Heart T-light Holder" allows for strategic inventory management and targeted marketing. The identification of less popular items, such as the "Natural Slate Heart Chalkboard," informs decisions for potential promotions or adjustments, ensuring a product lineup that resonates with customer preferences.

Revenue Optimization: Insights from revenue-related charts, including the bar plot of top revenue earners and the pie chart of invoice numbers, provide crucial information for revenue optimization. Recognizing high-earning products and top-performing invoices allows for strategic financial decision-making. Focused efforts on high-value transactions, like invoice no. 581483, contribute to revenue maximization and effective financial management.

Geographical Targeting: The bar plot showcasing unit prices across different countries aids in geographical targeting. Understanding pricing variations, especially the highest unit prices in Singapore, allows for tailored pricing strategies. This data-driven approach ensures optimal revenue generation in diverse markets, emphasizing the importance of geographical insights in strategic decision-making.

Customer Segmentation: The line plot illustrating sales trends in different countries over time and the bar plot highlighting quantities in various countries contribute to customer segmentation. Recognizing the UK's substantial sales volume prompts tailored marketing and inventory management strategies, considering its unique position. Identifying lower sales in other countries prompts targeted efforts for market expansion or adjustments, emphasizing the significance of customer segmentation for tailored strategies.

Operational Efficiency: The heatmap depicting quantities and final sales of top items contributes to operational efficiency. Recognizing the popularity of specific items allows for strategic inventory management and targeted marketing efforts, streamlining operations. This data-driven approach ensures the online store can effectively meet demand, enhancing operational efficiency and overall business performance.

In conclusion, the comprehensive analysis of diverse charts provides a multifaceted understanding of the online retail landscape. These insights empower the online store to refine its product offerings, optimize revenue streams, target specific geographical markets, tailor marketing strategies, and enhance operational efficiency, fostering sustained growth and customer satisfaction in the dynamic realm of online retail.
