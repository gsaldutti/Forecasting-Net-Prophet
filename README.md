# Forecasting-Net-Prophet
 
 
 
 ![PROPHET](prophet.png)





In the Assignment, I will assume the role of a growth analyst at MercadoLibre - a very popular e-commerce site in Latin America. With a task of analyzing the company's financial and user data, I need to find various ways to make the company grow. Using my newly acquired skills of forecasting the future with Prophet, I will predict search traffic and translate it into the ability to successfully trade the stock.


# Forecasting

Forecasting With Prophet 

How to install


## Overview of the project and project goals

The goal is to create a Jupyter notebook that contains all data preparation, analysis, and visualizations for all the time series data that the company needs to understand. Text and comments to document my findings, and answered the question prompts in the instructions, plot the results so that we can visually show illustrate the predictions.

![FORECASTING](forecasting.png)

## Software version control


### Libraries 
*  Pandas - is a software library designed for data analytics that makes it easier to work with data from practically any type of file. Pandas supplies powerful tools for working with time data in particular, and time is a key aspect of financial analysis. Analysts typically compare and measure financial assets—from single stocks to large portfolios—across time.
*  Prophet - is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.

* Following libraries were imported.
* The following dependencies were installed in order to use google colab.


![LIBRARIES](libraries.png)




### Interfaces

Google Colab is an Integrated Development Environment (IDE) that allows users to run Jupyter Notebooks in the cloud.

 
### GitHub
* Repository created on GitHub
* Files were committed using the command line in GITBASH
* My repository is organized to include resources folders with CSV files
* Jupyter Notebook with code, runs without errors.
* Answers on questions are included

### How to install

* Save the REPO from created in GitHub to the computer via the following path:

   cd/REPOs/Forecasting-Net-Prophet

![Local Path](path.png)

```
cd desktop

git clone https://github.com/gsaldutti/forecasting-net-prophet.git
```


* We will run a Jupyter Notebook in [Google Colab](https://colab.research.google.com/) 
*  Choose [ forecasting_net_prophet.ipynb ] file in Forecasting folder to see the analysis report.


[
<img width="1313" alt="Screen Shot 2021-06-07 at 6 28 55 PM" src="https://user-images.githubusercontent.com/80833988/121108225-3ad9d480-c7be-11eb-8e60-fcb9152c4c53.png">
](url)

The following code in the document promts you to Choose appropriate CSV file to access the data 

```
from google.colab import files
uploaded = files.upload()

```



### Particularly in "Step 1: Find Unusual Patterns in Hourly Google Search Traffic"


[
<img width="998" alt="Screen Shot 2021-06-07 at 9 56 59 PM" src="https://user-images.githubusercontent.com/80833988/121125361-4b4c7800-c7db-11eb-8a00-778394f414ab.png">
](url)



###  and "Step 3: Relate the Search Traffic to Stock Price Patterns"


[
<img width="1024" alt="Screen Shot 2021-06-07 at 10 00 02 PM" src="https://user-images.githubusercontent.com/80833988/121125637-b9913a80-c7db-11eb-930f-af3e5b03c9cf.png">
](url)



### Results and summary of the analysis

- Step 1.



[
<img width="1029" alt="Screen Shot 2021-06-07 at 10 04 19 PM" src="https://user-images.githubusercontent.com/80833988/121126006-50f68d80-c7dc-11eb-8330-ce86fe0b07a6.png">
](url)



- Step 2.



[
<img width="1057" alt="Screen Shot 2021-06-07 at 10 05 12 PM" src="https://user-images.githubusercontent.com/80833988/121126080-71264c80-c7dc-11eb-8a4f-bd21b416300a.png">
](url)



- Step 3.



[
<img width="1127" alt="Screen Shot 2021-06-07 at 10 06 26 PM" src="https://user-images.githubusercontent.com/80833988/121126184-9ca93700-c7dc-11eb-9d03-b54b4197905d.png">
](url)



- Step 4. 



[
<img width="960" alt="Screen Shot 2021-06-07 at 10 08 14 PM" src="https://user-images.githubusercontent.com/80833988/121126346-dd08b500-c7dc-11eb-8c48-73c1009fd72b.png">
](url)



- Explore the correlation:



[
<img width="958" alt="Screen Shot 2021-06-07 at 10 08 58 PM" src="https://user-images.githubusercontent.com/80833988/121126421-f873c000-c7dc-11eb-976c-ccede0e76c57.png">
](url)



- Forcast with Prophet



[
<img width="973" alt="Screen Shot 2021-06-07 at 10 09 53 PM" src="https://user-images.githubusercontent.com/80833988/121126503-18a37f00-c7dd-11eb-9c4e-2a7510a8c928.png">
](url)



- Slice and explore the data:



[
<img width="808" alt="Screen Shot 2021-06-07 at 10 12 18 PM" src="https://user-images.githubusercontent.com/80833988/121126692-6e782700-c7dd-11eb-808a-62f597a021d6.png">
](url)

[
<img width="979" alt="Screen Shot 2021-06-07 at 10 10 46 PM" src="https://user-images.githubusercontent.com/80833988/121126567-37a21100-c7dd-11eb-9b96-522d2a89998b.png">
](url)








