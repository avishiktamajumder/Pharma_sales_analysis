## **Pharmaceutical Analysis and Forecast Model 💊📈**

### **The Data**   
The dataset comprises of monthly sales figures (in USD) of the R03 drug in United States of America, which corresponds to the category of drugs for airborne diseases. The dataset contains sales figures of 324 months, from January 1992 to December 2018.   
Link to the dataset - [Pharmaceutical Monthly Sales (Kaggle)](https://www.kaggle.com/datasets/073a504d1a08699891aa3dc261341d697c85513651c2f0a428ae0162873f8762)

### **Data Preprocessing**   
The sourced data was put through basic exploratory functions which helped us understand the volume of the data and deduce if there were any null values present. The date object values were converted to datetime values and the date was set as the index to perform subsequent time series analysis and forecast functions. The Simple Moving Average with a window size of 4 weeks is used  to smoothen the curve and analyse the trend of drug sales.   

### **Data Modelling**   
The ACF and PACF values are plotted and analysed as per the values in the dataframe. A suitable model is chosen to fit the dataset. The AR model is used to forecast the sales of the R03 drug for the next 3 months, according to the training data split. The training data, forecast and the actual test data are plotted. The difference between the forecast values and actual values is analysed using Root Mean Square Error and plotted for analysis.
