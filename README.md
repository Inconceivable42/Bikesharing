# Bikesharing
---
DataSource: 2022-ciibike-tripdata.csv
Tools:  * Python/Pandas
        * Jupyter Notebook
        * Tableau Public

---
## Overview
The scenario behind this exercise is that I am using data from Citibike, a New York City bikesharing company, to convince an angel investor to invest in the creation of a new biksharing program in Des Moines, IA.
---
---
## Analysis
Data from the month of August is being used for this analysis, a month where weather in both NYC and Des Moines are conducive to riding bikes. Being that NYC and Des Moines are quite different, I am focusing on aspects of the business that are transferable between metropolitan areas. The key categories of data are bike usage times of day and duration of use; whether the user is a subscriber or not; types of places to locate bike stations; and gender of users (primarily for marketing reasons).
---
---
## Results
---
(https://public.tableau.com/shared/T5GFKCPCM?:display_count=n&:origin=viz_share_link)
---
### Bike Usage
---  
(https://public.tableau.com/shared/7CBJDHWDM?:display_count=n&:origin=viz_share_link)
---
The peak times of bike usage are the Monday through Friday morning and evening commutes. The highest number of starts occur between 5:00 and 7:00 PM followed by 8:00 to 9:00 AM. Thursdays have the most usage. 
---
(https://public.tableau.com/shared/466CNDF7B?:display_count=n&:origin=viz_share_link)
---
On the weekends, usage is more consistent during the day. Saturday usages pick up after 9:00 AM and starts to trail off around 9:00 PM. Sunday usage starts a bit later with more users starting in the 10:00 AM hour and starting to trail off around 8:00 PM. 
---
(https://public.tableau.com/shared/MBQZMKGK3?:display_count=n&:origin=viz_share_link)
---
The majority of rides are less than an hour, with around 10 minutes being the most frequent length.
---
### User Types
---
(https://public.tableau.com/shared/Z45S5HQDC?:display_count=n&:origin=viz_share_link)
---
The majority of rides are taken by subscribers to Citibike. Subscriber usage is throughout the week with the busiest usage being Monday through Friday commute times. Weekend usage is lighter but steady throughout the day.
Customers are more likely to use Citibike on the weekends. Customers are also more likely than subscribers to be of unknown gender. In fact, 85% of unknown gender rides were customers. 
---
(https://public.tableau.com/shared/BBY99M6Y5?:display_count=n&:origin=viz_share_link)
---
Unknown gender rides were more evenly distributed between the 10- and 30-minute lengths. From that we can infer that the majority of those are customers.
---
### Locations
---
(https://public.tableau.com/views/Challenge14_16580445990340/NYCinAugust?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
---
The most used start stations used by subscribers are south of Central Park, with the station used the most being outside Grand Central Station. 
The two stations most used by customers are on the south edge of Central Park.  
---
---
## Summary
By analyzing what is working for Citibike in NYC, I see what data about Des Moines is needed to convince an angel investor to commit money to this startup. If I follow the model of subscribers using the bikes to commute to and from work, I need data on central start and end points. I need to identify where people live or where public transportation drop riders and where are most people working. To round out weekend usage, I need to identify the recreation areas and/or tourist attractions. 
---
Most rides by subscribers are done by males. I would use information as I steer marketing towards potential male users. I would also get our information out to tourist and public transportation riders.
---
I was unable to decern from the Citibike data how many individual subscribers or customers are using the bikes and how often. Visualizations showing rides per person and also how often an individual uses a bike would be valuable in determining price points for subscriptions or individual customer usage.
