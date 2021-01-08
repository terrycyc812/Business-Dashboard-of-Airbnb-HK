# Business Dashboard of Airbnb(HK)
 To build a dashboard for senior management to monitor the business condition of Airbnb(HK) with a single click on the interactive charts.
 
## Data source
 Data is obtained from [Inside Airbnb](http://insideairbnb.com/get-the-data.html) compiled on 25 Oct, 2020. Since no booking data is provided, revenue cannot be calculated to reveal the actual business performance. 
<br>


## Overview
<img src='images/1a.png'>

- Nearly half of the listings are concentrated in Yau Tsim Mong district, the center location of HK
- The most expensive listing is located in Yau Tsim Mong district, with an abnormally high price (81K per night)
- The most common room type in HK is private rooms


If only focus on the New Terrotories (including outlying islands), 

 <img src='images/1b.png'>
 
 - Listings are concentrated most in Islands district, probably searving the needs of holiday accommodation
 - Listings are also concentrated in North district, which is a good choice for people frequently travelling to mainland China
 - More than half of the room type is entire home/apartment
 <br>
 
## Pricing
<img src='images/2a.png'>

**From "*District by Median Price*" section (top-right)**<br>
- Southern district has the highest price level
- Central & Western district has an unexpectedly lower price level than Kwai Tsing and other 2 districts 


**From "*No. of Listings by Price Range*" section (bottom)**<br>
- Nearly half of the listings fall in the price range of $300-$1000, distributed in all 18 districts
- Around 37% of listings fall in the lowest price range (<$300), distributed in all 17 districts except Kwai Tsing
- 47 listings fall in the highest range (>$10000), distributed in 10 different districts
<br>

## Reviews

<img src='images/3.png' height=400>

**From "*Covariance with Rating*" section (top-left)**<br>
- Cleanliness has the highest covariance with the final rating of a listing. This aspect is the major concern of the customers
- Location has the lowest covariance. Customers will not count too much when rating a listing


**From "*Review Count of each Price Range*" section (right)**<br>
- The highest review count falls in the lowest price range. 
<br>

## Availability

<img src='images/4a.png' height=500>

**From "*Count of Instant Bookable Listing*" section (top)**<br>
- If consumers want to book a listing instantly, private room in Kowloon will be a good choice
- Most of the listings in outlyig islands require pre-booking

**From "*Availability by Month*" section (botton-left)**<br>
- The availability in 12/2020 is still high. COVID-19 may still have a severe impart on the booking even there is a Christmas holiday
- There is a drop of availability in 02/2021. It may be due to the Chinese New Year Holidays, with higher demand / less supply


The availability of individual district can be shown by a single click

<img src='images/4b.png' height=500>
<br>

## Hosts

<img src='images/5a.png' height=500>

Airbnb has a superhost scheme to encourage the hosts to provide the best hosting service. From the top section, superhosts can provide better services (so higher rating) with cheaper prices. It is suggested for customers to search for listings from superhosts in order to enjoy an valuable experience. 

By selecting the filter, it is easy to find out the listings from all superhosts. 

<img src='images/5b.png' height=500>
