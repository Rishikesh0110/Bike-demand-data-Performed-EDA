
# Exploratory Data Analysis on Bike share demand :
This project is performed to check how the business of Bikes are running ,Compared two years to check, is there any increment of business or not ,And also checked which hours and which season,Month,Days business is at peak.




## About the data
DataSetInformation: https://www.kaggle.com/competitions/bike-sharing-demand/data
YouareprovidedhourlyrentaldataspanningtwoyearsforBikeSharing
## Used tools and techniques to perform this EDA
For withdraw insights from the data ,we must have the following python liberies installed to analyse data deeply.

Numpy: NumPy (Numerical Python) . https://numpy.org/doc/stable/user/absolute_beginners.html

Pandas:  https://pandas.pydata.org/docs/

Seaborn: https://seaborn.pydata.org/

Matplotlib:  https://matplotlib.org/

Sklearn: Simple and efficient tools for predictive data analysis https://scikit-learn.org/stable/

Google Analytics Colab

## Questions that derived
Some strong questions are:
1. In which season the bike rental business is at peak and for which season it went at bottom?
2. What is the specific time b/w the day in which business is at peak and bottom?
3. Which is most profitable either weekend ,Holidays or weekdays?
4. How many there are reguler registered users and the casual users of bike?
5. Which year has high demand of bike rental services, is there is any increment in business from last year or not?
6. Which month has high demand of bike rental services?
7. 
## Various methods to perform EDA
After suscessfully loading the libraries , need to understand the data carefully.
DataFields
1. datetime-hourlydate+timestamp 
2. season- 1=spring,2=summer,3=fall,4=winter  
3. holiday-whetherthedayisconsideredaholiday 
4. workingday-whetherthedayisneitheraweekendnorholiday ● weather-1:Clear,Fewclouds,Partlycloudy,Partlycloudy 2:Mist+Cloudy,Mist+Brokenclouds,Mist+Fewclouds,Mist 3:LightSnow,LightRain+Thunderstorm+Scatteredclouds,LightRain+Scattered clouds 4:HeavyRain+IcePallets+Thunderstorm+Mist,Snow+Fog 
5. temp-temperatureinCelsius 
6. atemp-"feelslike"temperatureinCelsius 
7. humidity-relativehumidity ● windspeed-windspeed ● casual-numberofnon-registereduserrentalsinitiated ● registered-numberofregistereduserrentalsinitiated ● count-numberoftotalrentals

 # Steps and Techniques
1. First Load the required liabraries which are used for data analysis such as pandas, numpy ,Matplotlib, Seaborn
2. Than loaded the data from local machine by hel of pandas as it provide functions such as pd.read_csv("path_name")
3. Than checked first five rows and last five rows by head() & tail () commands.
4. Than checked the informartion of the data by info() fuction which summerise about every columns such as null values & lengts.
5. Than checked shape of data to get the actual lengh of  rows and columns
6. Than Checked stistical analysis for string or categorical columns bu df.describe(include="O")
7. Than also returns the each column names and stored as list seperatly as categorical columns and numerical colums. 
8. Performed Statistical analysis of data by driving 5points analytics by Describe function.
9. **Exploratory data analysis**
1. Now started the EDA part to mining the data by visualization of each columns.
2. Ananlysis of each numerical columns and categorical columns to derive insights by using diffrents pandas and numpy functions.
3. Visualiing those insights to make it interactive by diffrent techniques of Seaborn and Matplotlib by charts such as Histogram,Distribution plot ,Box plots for each nuerical columns and countplots for each categorical colums.
4. Sucessfully derive all the possible insights from the data with multiple trends ,that how the bbuisiness is going and how we can improve in functions.
5. Derived insights such as a trend that which season is better for business and which of the time business went on peak points by help of line diagrame.
6. Some other insights Such as how many registered usres and temporary users are their and visualize them.
7. Tried to derived correlation b/w some of columns to find relationships by using Heatmaps and regplots.
   **Data wranggling**
1.  Removing np.nan values of missing values by replecing with specific mean or median of the column.
2. That checked for duplicates by trying to find the shape of dataset again after applied drop_duplicates().
3. Than handled outliers for each numerical columns the make the data more accurate and need to set the column to represent by their mean.
   **Handling columns of Standrization of each numerical and categorical columns**
1. Than handled categorical columns by One hot encoding pd.get_dummies() and numerical columns by minmax scaler and stadard scaler to standarize numerical columns.

    # Conclusion
   So defined every possible insights that can be derived from the data, to analyse the Bike rental business which tells some most important questions for the business.
