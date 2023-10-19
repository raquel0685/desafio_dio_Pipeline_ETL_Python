<img src="bootcamp.png" width="100" alt="Logo Santander Bootcamp 2023" align="left"/>

# ETL pipeline using the [*Chocolate Bar Ratings*](https://www.kaggle.com/datasets/rtatman/chocolate-bar-ratings/data) dataset  

### This was an activity proposed in the *Exploring Generative AI in an ETL pipeline with Python* module of the *Santander Bootcamp 2023 - Data Science with Python*  

This dataset was downloaded from *Kaggle* and contains expert ratings of over 1,700 individual chocolate bars, with information on their regional origin, percentage of cocoa, the variety of cocoa beans used, and where the beans were grown. The grades varied between 1 and 5, with 3.75 being considered a bar of "praiseworthy" chocolate.  
The data was extracted using *GoogleColab*, and it was checked for nulls, duplicates, and discrepant values. The *Bean_Type* column was removed due to the high amount of nulls, and the 
*Cocoa_Percentage* column was turned into a *float* type and values bigger than 100 were excluded. After the assessment, 8 columns and 1,714 registries remained.  
We created four tables to identify the companies, regions, countries, and cocoa percentages that received the best ratings and extracted them to *.csv* files.
