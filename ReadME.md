# FOOTBALL TRANSFERS ANALYSIS IN EXCEL  

### Preview of data set  

This football data set contain two sheet,one for database of about 3500+ rows and 7 column and the other sheet contained the country.
The aim of this project is to analyze and know the top 5 European countries with the highest number of incoming transfers.
  
#### Project Walk Through  

I started by reviewing the data set for errors checking   

![alt](/image/picture%2001.jpg)  

I started in the countries sheet by splitting the data using Text-to-columns tools,chose the Delimited file type and select ‘comma’ as delimiter.

Next I switched to the database sheet where i thoroughly check for errors and discover where 2028 was written instead of 2023,I used find and replace tools to correct them

![alt](/image/picture%2002.jpg)  

And finally I filled in the continent column in the database sheet by using excel vlookup function  

![alt](/image/picture%2003.jpg)  

I Analyzed the aggregate number of European transfers by creating a new sheet and populated it by using excel sumifs functions  

![alt](/image/Picture%2004.png)  

Again i created another new sheet to analyzed European transfer by country which I also populated by using sumifs function  

![alt](/image/Picture%2005.png)  

Again to know the first five highest transfer I applied the rank function in excel  

![alt](/image/Picture%2006.png)  

After which the number of incoming transfer for the countries was found in a separate sheet  by using the sumif excel function And also the average transfer fee was found by dividing the total number of incoming transfer by the number of transfers.  

![alt](/image/Picture%2007.png)  

And finally the visualization was done using a combo chart the ‘Average transfer fee’,was added as a secondary axis to show the Average transfer fees per country separately  

![alt](/image/picture%2008.jpg)  


## DISCUSSION

After the analysis was done it was discover from the above chat
that England has the highest number of incoming transfers with the number of incoming transfer of 1,020 and with the average fee of about 2 million follow  by Germany with average fee of 9 million $ with the number of incoming to be about 664,followed thirdly by Italy with the number of incoming transfer to be around 542 with average fee of 1.6 million ,Spain took the fourth position with the number of transfer of 476 with average fee of 1.2million  And France sitting at the fifth highest transfer with the number of transfer to be 438 and with average fee of 1.7million 


