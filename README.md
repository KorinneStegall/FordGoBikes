# ford_go_bikes
The Ford Go Bike System data set includes information about
individual rides made in a bike-sharing system covering the greater San Francisco Bay area. I
used travel information, like rider gender, rider age, distance traveled and ride duration to 
find out who is using Ford Go Bikes, how far they are traveling and for how long. 

### Wrangling
I cleaned the dataset and created new columns I saw fit for better analysis. Some examples of 
added columns include distance traveled and duration. I extracted distance traveled by taking
the longitude and latitude of the start and end stations and the earth’s radius, and then 
calculated using the haversine formula how far a bike travels. I also took duration in seconds 
and converted it into minutes for better analysis.



### Findings
Some of my main findings were that females between the ages of 26 and 34 traveled more than
males, and the age group 26 - 35 traveled the most in general. Another thing I
found was that most trips were no more than 1.5 miles and 20 minutes no matter the age group
or gender. Additionally, although there were more males in this dataset that traveled further
and longer than females, on both average distance and duration, females traveled longer and 
further than males. Lastly, when it comes to when users are traveling, I found that more users
travel during weekdays than on weekends if they are subscribed to the system. Therefore it can
be concluded that subscribers probably use the system for daily work commute rather than for
leisure. 

#### References used in project:
https://stackoverflow.com/questions/33029396/using-pandas-to-calculate-distance-betweencoordinates-from-imported-csv
https://www.kaggle.com/residentmario/bivariate-plotting-with-pandas
