
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

#Steps
1. Statistical analysis of data by driving 5points analytics by Describe function.
2. Ananlysis of each numerical columns and categorical columns to derive insights by using diffrents pandas and numpy functions.
3. Visualiing those insights to make it interactive by diffrent techniques of Seaborn and Matplotlib.
4. Sucessfully derive all the possible insights from the data with multiple trends ,that how the bbuisiness is going and how we can improve in functions.
5. Data wranggling : Removing np.nan values and outliers with duplicates from the dataset.
6. Than handled categorical columns by One hot encoding pd.get_dummies() and numerical columns by minmax scaler and stadard scaler to standarize numerical columns.