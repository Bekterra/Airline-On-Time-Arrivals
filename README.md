# Airline-On-Time-Arrivals
Use the US Dept. of Transportation on-time arrival data for non-stop domestic flights by major air carriers to predict arrival delays.

Build a binary classification model for predicting arrival delays or a regression model that predicts the extent of the delay.  Do not use departure delay as an input feature.

The data I chose is for a full year extending from December 2015 to November 2016. 
Variables that I used:

    Year
    Month
    DayofMonth
    DayofWeek
    UniqueCarrier
    OriginAirportID
    DestAirportID
    CRSDepTime (the local time the plane was scheduled to depart)
    CRSArrTime (the local time the plane was scheduled to arrive)
    ArrDelay (how early/late the plane was at its final destination in minutes: our target variable)
    Distance (how far did the plane travel for the route)
    CRSElapsedTime (the scheduled difference between departure and arrival)
