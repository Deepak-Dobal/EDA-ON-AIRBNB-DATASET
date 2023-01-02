
# EDA on Airbnb Bookings AnalysisbyDEEPAK DOBAL

A brief description of what this project does and who it's for

# Project Summary
Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present a more unique, personalized way of experiencing the world. Today, Airbnb became one of a kind service that is used and recognized by the whole world. Data analysis on millions of listings provided through Airbnb is a crucial factor for the company. These millions of listings generate a lot of data - data that can be analyzed and used for security, business decisions, understanding of customers' and providers' (hosts) behavior and performance on the platform, guiding marketing initiatives, implementation of innovative additional services and much more.

# Problem statement

What can we learn about different hosts and areas?

What can we learn from predictions? (ex: locations, prices, reviews, etc)

Which hosts are the busiest and why?

Is there any noticeable difference of traffic among different areas and what could be the reason for it?

# THE COLUMNS
Id- It provides a unique id to each listing in the dataset.
Name-It describes the property in a concise manner.
Host_id-It is used to ascertain the ownership of a certain individual
Host_name-It is the name of the property owner
Neighbourhood_group-It basically categorizes neighbourhood into  five groups Bronx,Brooklyn,
Manhattan,Staten Islands and Queens 
Neighbourhood-It designates the location of a property.
Lattitude-It Specifies the Lattitude of the property.
Longitude-It denotes the Longitude of the property.
Room_type-It classifies the type of property into Private_Room,Shared_Room and Entire_Apartment.
Price- It provides the price of each listed property.
Minimum_Nights-It gives the minimum night one needs to pay for in the property.
Number_of_reviews-It is used to ascertain the number of reviews received by a property.
Reviews_per_month-It denotes the number of reviews per month.
Calcuated_host_listings_count-It corresponds to the number of properties hosted by the unique host_id
Availability_365-The number of days the property is available in a year.

# Conclusions

So, this AirBNB dataset is a rich in data but not on features. From the entire above analysis we can conclude that.
1-Most visitors don't prefer shared rooms, they tend to visit private room or entire home.

2-Manhattan and Brooklyn are the two distinguished, expensive & posh areas of NY.

3-Though location of property has high relation on deciding its price, but a property in popular location doesn't it will stay occupied in most of the time.

4-Performing a regression on this dataset may result in high error rate, as the features given in this dataset, are of very poor quality in deciding the property valuation. We can see this by looking at correlation heatmap. We would need more features like bedrooms, bathroom, property age (guessed it'd be a very important one), tax_rate applicable on land, room extra amenities, distance to nearest hospital, stores or schools. These features might have a high relation with price.

5-We could use a time series analysis to make prediction of occupancy rate at particular time of a month, or particular time of a season.

6-It'd be a better if we had avg guest ratings of a property, that would be beneficial in understanding the property more and could also be a factor in deciding price (a low rated property tends to lower their price)



