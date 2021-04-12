# bikesharing

## Resources

Tableau Public 2021.1, CSV of Citi Bike ride data from August 2019

## Overview

Inspired by the success of bikesharing services across the country, a client wishes to start a bikesharing company in Des Moines, Iowa.  To gain some insights in preparation to start this business, the client requested visualizations of data collected by Citi Bike in New York City for the month of August, 2019.  From these visualizations the client wants to gain insights into whether gender affects ridership, want times of day and what days of week are the busiest, and thus what riders are likely using the bikes for.  This will help the client target and scale their business in Des Moines.

I used Tableau Public to create a story from the visualizations requested.  Images of the visuals used are copied below, and the full Tableau Story can be viewed [here](https://public.tableau.com/profile/michael.hertel#!/vizhome/NYCCitiBikeChallenge_16181110490760/Story1).

## Results

- User Type

As can be seen in the bar graph below, the vast majority of rides in New York City were taken by subscribers to the service, while far fewer were taken by riders who do not have a subscription.

![user type](resources/slide_1.png)

This indicates that the client should offer a subscription as part of their service, and they should focus their promotional energy on getting people to subscribe.
- User Gender

Most of the riders in NY were male, while a only about a quarter were female.  A small portion did not report their gender.

![user gender](resources/slide_3.png)

This indicates the client in Des Moines should focus promotions on getting male subscribers.

- Trip Length
    - All users

    The following visualization shows that most trips are less than an hour in length, and in fact the majority of those rides are only a few minutes long.  (Note, when viewing the interactive visualization in Tableau the graph can be filtered by hour of duration, ie 0 hours and x minutes, 1 hour and x mintes, etc.) Hundreds of thousands of rides lasted less than an hour, while fewer than 1,000 rides were between 1 and 2 hours, with each subsequent hour accounting for fewer rides after that.

    ![trip length](resources/slide_2.png)

    The relatively short trip duration means the client in Des Moines means the number of bikes needed, even during peak hours, will be relatively low, as most bikes will be able to be used by multiple clients per hour.

    - Effect of Gender
    
    The client wanted to know if gender seemed to affect the other factors such as trip length.  The below visualization breaks down trip length by gender.  While males do account for most rides, trip length seems to follow the same pattern as above regardless of the rider's gender

    ![length by gender](resources/slide_4.png)

- Trip Purpose

    The client wanted insights into the likely uses of bikes by customers, so I created visualizations showing what time of day and what days of the week accounted for the most rides, to see if that could provide insight.

    - Time of Day

    Trip start times are much higher during the daytime, with the peak times being between 7:00 and 9:00 A.M. and 5:00 and 6:00 P.M.  This indicates that a large portion of riders are using the bikes to commute to and from work.
    

    ![start time](resources/slide_5.png)
    
    - Day of the Week

    I broke down the start times by day of week as well with the below heatmap.  Here, the same peak hours show to be true on the weekdays, with fewer rides in general happening on weekends.
    
    ![trip day](resources/slide_6.png)

    - Effect of Gender
    
    As with trip length, when viewing the weekday data according to gender, riders seem to follow the same pattern of peak usage regardless of gender.  Note, because so many more males ride than females or unknown, when viewing each gender side by side in the interactive visualization, the color scaling is difficult to see for females.  The pattern becomes much clearer when viewing genders one at a time.

    ![trip day gender](resources/slide_7.png)
    ![female](resources/slide_7a.png) 
    ![male](resources/slide_7b.png)
    
    - Effect of User Type

    While gender does not seem to affect the purpose of the ride, when charting subscribers along side non-subscribers (similarly viewed one at a time for color grading) the heat maps show that subscribers use bikes for work commuting during the week, while the occasionaly rider who does not subscribe is more likely to ride on the weekend.
    
    ![subscribers](resources/slide_8a.png)
    ![non-subscribers](resources/slide_8b.png)

- Trip Location

The map below plots each of the bike stations on a map of New York, with larger markers representing more rides originating from that location.  It is clear in this visualization that most rides in New York originate in Manhattan, with areas along the coast close to Manhattan in other buroughs also seing many rides.  

![location](resources/slide_9.png)

Manhattan is both densely populated and has many businesses, so rides are likely starting and ending within the burough for people living there and commuting a short distance to work.  The high number of trips originating along coastlines of  other buroughs could due to people driving longer distances to near Manhattan, then using a bike to commute into Manhattan.

This indicates that the client in Des Moines should place most stations in areas around a downtown or other business hub, as well as placing a few centerally in more residential areas.  This would provide locations from which to begin their commute to work.

## Summary

In conclusion, the data taken from Citi Bike in New York City indicates that most rides are taken by customers who subscribe to the service to use for work commuting.  If Des Moines is likely to follow suit, then the client there should focus building the infastructure and promotions for their business around commuters.

However, New York City has a long tradition of public transportion such as buses and subways.  Consumers' habits were already shaped around commuting via public transport rather than individual cars.  This likely made the adoption of bike sharing an easy transition that allowed companies like Citi Bike to find quick success.  

It would be helpful for the client to examine Des Moines usage of public transportation in comparison to New York's.  By acquring data on how workers commute in both New York and Des Moines, a grouped bar chart showing New York and Des Moines usage side by side for transportation types such as bus, cab, train, and personal automobile could clarify whether Des Moines commuters might be as likely to adopt bike sharing as prominently.  If Des Moines usage of personal automobile over various public transportation types is proportionally higher than New York's, then Des Moines workers might be less likely to adopt the bike sharing option.  Thus, the client in Des Moines might need to take a different strategy in promotion and infastructure.  However, if Des Moines residents show a similarly strong usage of public transport over car, then the client would do well to plan around commuting workers, using New York as a model.

Another helpful visualization would be a bar graph showing the total population of New York along side the number of Citi Bike subscribers.  This could provide insight into what percentage of the population is likely to use the service, allowing the client in Des Moines to scale the business to an effective size for Des Moines' population.








