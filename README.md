# LSE_DA201_assignment_notebook_Tuna_Tuncay
COVID-19 Analysis Using Python

Analsis is based on 3 data sets: Cases, vacinnated and tweets.

Cases: a. 7584 rows and 12 columns. b. Death, Cases and recovered values are cumulative sums. Hospitalized values show number of people in hospital on certain date. c. Dataset has only 2 rows of missing data.(Bermuda for dates 2020-09-21 & 2020-09-22) e. DataFrame has default index starting from 0.

Vaccinated: a. 7584 rows and 11 columns. b. Values show number of people received shots on certain dates. (Not cumulative vaccinated numbers) c. There are no missing values. f. DataFrame has default index starting from 0.

Tweets: a. 3960 rows and 21 columns. b. Several missing values for all rows. c. DataFrame has default index starting from 0.

Pyhton notebok has visuals and tables that shows how death, case and vaccinated numbers are evolving over time. 

Twitter data set is analyzed to identify people's perception on Covid and Vaccination.

Simply forecasting is applied on hospitalisation numbers by using moving average method with window size 7.

Detailled findings can be found in assignment report.
