**Project name:**  
Production Yield Analysis

**Project Description:**  
In a highly complex and dynamic production environment, yield engineering plays a crucial role in ensuring the increase of the good parts produced, 
but also learning from the failures that occured and adjusting the systems so that those losses are avoided in the future. An important part of 
yield engineering consists of making sure the activities in production can be tracked by means of data and analysing that data on a regular basis. 
This project aims showing a small part of this exciting part of production engineering and providing the basic knowledge of yield data analysis.
The initial dataset is a typical SAP stored production data received from the MES (Manufacturing Execution Systems) application. 

**Project Overview:**
1. Load required Libraries  
2. Load the DataFrame 
3. Understanding the DataSet and Data Wrangling  
    3.1. Remove the unfinished Orders  
    3.2. Add the Operational Yield  
    3.3. Add the Cumulative Yield  
    3.4. Add the Shipping Dates to the DataFrame  
4. Plotting the Data  
	4.1. Operational Yield Barplot  
	4.2. Cumulative Yield Barplot  
	4.3. Material Flow Chart  
    4.4. Investigate the Correlation between Starting Amount and FPY (First Pass Yield)  
    4.5. Investigate the Operational Yield AVG per Month  


**Libraries used:** 
* pandas
* numpy
* matplotlib
* seaborn