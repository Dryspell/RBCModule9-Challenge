# RBCModule9-Challenge

## Overview of the Analysis
This analysis is meant to exemplify the basic usage of SQLAlchemy and SQLite through the scenario of a Hawaiian surf shop opening. Accordingly, the simulated client is looking for basic temperature summaries to determine if the business will be sustainable year-round.

## Results
For our results, we refer to the following table:

| June | December |
| :-: | :-: |
| ![juneTemps](juneTempsDF.PNG) | ![decTemps](decTempsDF.PNG)

As we can see from the two tables, the temperature in Hawaii is remarkably consistent with the mean temperature only dropping by 4&deg;, a 0.5&deg; difference in standard deviation and the minimum dropping by 8&deg;, the maximum dropping by 2&deg;. These differences should be very minor for any would-be surfer.

## Summary
In conclusion, we see that Mr. Avy should have no problem sustaining his Hawaiian business through the winter months. A further query we could do would be to separate the data by station so as to determine which Hawaiian island might be better situated. We could also determine which months have the most percipitation and see how it compares against our temperature data. 