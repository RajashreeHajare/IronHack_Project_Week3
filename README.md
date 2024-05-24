Brief description of the project:
This is project is built around the dumpy data on Global Superstore is acquired from data.world site. 
The situation here in this work is that there exists an imaginary company named "TechieWorld Superstore" providing office essentials to the population of United States. The company began in 2010 and since then it has been aggressively advertising  to reach its target sales. Hence they bring their 4 year data to our team of data analysts to re-evaluate their sales startegy by gaining insights from their existing collated data. 


Installation instructions:
You basically require ipykernel and Jupyter.

Note: You require a new environment "enev to be activated before you start working with your Juputer lab. 

Data source: 
Here is the link:  https://data.world/2918diy/global-superstore

Description of the data: 
There exists a single csv files named raw_global_superstore data with nearly rows: 51290 & columns:27. However, I only used United States data set for my study, using 9994 rows and 27 column data set.

Pre-processing steps: 
1. Structuring data : column rename - remove space and convert to existing column names to lowercase 
                      column rearrangement 
                      changing order_date and shipment_date using Datetime
		
Cleaning data and export : relatively clean data, you need some metrics to be calculated like gross price and net price to do perform calculations for the study.  
                           remove unwanted column ""ji_lu_shu"
                           export cleaned data file to csv (named: df_stores_cleaned)

Data verification :     confirmed and verified data using google sheets 
                                         


EDA : Studied basic Net sales and profit performance for 4 years and then dived deep into cutsomer segmentation, customer loyalty and product distribution understanding across net sales and        profit. 

Data Visualization: used bar plots, line plots, stack area plots, scatter plots, and  bubble plots. 

Current important findings: 

General Business Strategies
(a) Evaluate Cost Structures:  Reassess the cost structure for underperforming  products, especially tables, bookcases, and machines.
(b) Seasonal Planning: Increase Seasonal Staffing - Hire additional staff during Q4 to handle the increase in orders and shipments efficiently.
(c) Product Category Improvements:  Furniture Segment-  Re-evaluate the business strategy for the furniture category.
(d) Customer Focus:  Improve Supply Chain Efficiency - Implement strategies to enhance supply chain efficiency to maintain or increase average order value.
(e) Attract New Customers: Re-evaluate market trends to stay relevant and attract new customers.
(f) Marketing and Sales: Enhance Product Offerings by continuous update and diversification of the product offerings to cater to a broader customer base and adapt to market changes.
                   


