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
-Over the 4-years, there is a stead rise in profit and Net Sales 
- Net Sales shows sudden rise post 2012 but the rise does not seem to correspond with profits
- Quarterly variations in Net Sales, Discount and Number of orders place is similar. Q4 (Quarter 4) – shows highest rise in all 3 categories which is mainly due to festival and/or holiday season. Such seasonality demands  for more staff for handling orders and shipment process.
- Technology category is the most successful segment, making it strategically important 
- Office supplies seems to do fairly well in terms of sales but profit is limited; bulk purchases should be targeted more allowing  shipment cost to be reduced
- Furniture showed lowest profit and business strategy needs to re-evaluated 
- In 4 years, there is rise in orders and customers but fall in average order value, indicating supply chain efficiency is critical  for success
- Fall in rate of new customers indicate: (a) re-evaluation of market trends  (b) update existing product lists (c) revise marketing strategies
- Majority customers contribute <5000$ Net sales and < 1500 $ profit 
- In terms of profit: Furniture : under - performing: Tables*  & bookcases; Major contributors : Chairs , furnishings
                      Office supplies: under - performing : supplies; Major contributors : Copiers 
                      Technology : under - performing : machines*; Major contributors :  Phones, Accessories 
                      Note: * Sales seems to be moderate and therefore cost needs to be re-evaluated                            


