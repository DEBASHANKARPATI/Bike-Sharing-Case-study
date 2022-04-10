# Bike sharing case study assignment
> This project is about building a machine learning model using linear regression algorithm using  recorded transactional data of a bike sharing company called boom bikes .
> Where we basically need to predict the demand of the clients using factors mentioned in the data set.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- .
Target client BoomBikes is a bike sharing company , BoomBikes aspires to understand the factors taht affect demand of shared bikes after quarantine situation ends across the nation due to Covid-19 , and use those factors to stay ahead of the market compitition in a post COVID american market .
<BR>What are shared bikes ?
<BR>Shared bikes are the bikes which a person can take for rent ,or free and returns the bike before/on the stipulated time , on the platform ("dock") belonging to the same company , in our case to the Boombikes .
<BR> We have given a dataset named day.csv , which is a day wise transactional data describibg the factors which affects the total client counts.
<BR>The Dataset is containing the following columns or variables , which are described in the data dictionary Readme.txt , let's look into those.
<BR>instant: record index<BR>dteday : date
<BR>season : season (1:spring, 2:summer, 3:fall, 4:winter)
<BR>yr : year (0: 2018, 1:2019)
<BR>mnth : month ( 1 to 12)
<BR>holiday : weather day is a holiday or not
<BR>weekday : day of the week
<BR>workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
<BR>weathersit :
<BR>1: Clear, Few clouds, Partly cloudy, Partly cloudy
<BR>2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
<BR>3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
<BR>4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
<BR>temp : temperature in Celsius
<BR>atemp: feeling temperature in Celsius
<BR>hum: humidity
<BR>windspeed: wind speed
<BR>casual: count of casual users
<BR>registered: count of registered users
<BR>cnt: count of total rental bikes including both casual and registered
<BR>Here Our target or dependent variable is cnt and all other variables are predictors or independent variables

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
<BR>There is almost equal distribution of data on all the season.`
<BR>In both the years the population is distributed almost equally.
<BR>In given datset working days are more than non working days.
<BR>Distribution of population is zero for the very bad weather , and lesser for bad weather and increasing significantly with better weather.
<BR>Distribution of population is very less toward the extreme points of feeling temprature , and increasing towards mean temprature which is ~24 degree celcius.
<BR>In given datset mean of the total client is 4508 , can be as min as 22 and as max as 8714 per day.
<BR>There is a huge fall in the demand or total clients in spring in 2018 and 2019.
<BR>There is a huge boost in the demand or total clients in 2019 in comparision to 2018 , which can be a sign of increasing popularity of the brand.
<BR>The demand of shared bikes are more in case of working days in comparision to non working days , might be more people are using shared bikes for commuting to workplace or <BR>people are not travelling much if it is not as necessary as somthing like work as this data is recorded in COVID.
<BR>The demand of shared bikes are more in case of very good weather condition and null for very bad weather condition .
<BR>The demand or total clients are higher in a normal heat index of 20 to 35 , above or below of this range number of clients are decreasing.
<BR>The demand or total clients are significantly higher in a very good weather condition of across all the seasons.
<BR>The demand or total clients are significantly higher in 2019 in comparison to 2018 across all the seasons.
<BR>The demand or total clients are significantly higher in working days in comparison to non working days except summer season .
<BR>The demand or total clients are significantly higher in Very good weather condition irrespective of the year.
<BR>The demand or total clients are significantly higher in Very good weather condition in comparison to bad weather condition irrespective of the working / non working day .
<BR>The demand or total clients are significantly higher in working days in comparison to non working days irrespective of the year.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

<BR>pandas '1.2.4'
<BR>numpy '1.20.1'
<BR>seaborn '0.11.1'
<BR>matplotlib '3.3.4'
<BR>statsmodels '0.12.2'
<BR>sklearn '0.24.1'

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
https://en.wikipedia.org/wiki/Heat_index * Used for researching about heat index and wind chill
## Contact
Created by [@githubusername] - feel free to contact me!
