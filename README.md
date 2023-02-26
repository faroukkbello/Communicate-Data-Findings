# Ford GoBike Dataset Exploration
## by Farouk Bello

## Dataset
The dataset was provided for download on the project workspace and it is out individual rides made in a bike-sharing system covering the greater San Francisco Bay Area. Each trip record includes:

- Trip Duration (in seconds)
- Start Time and Date
- End Time and Date
- Start Station ID
- Start Station Name
- Start Station Latitude
- Start Station Longitude
- End Station ID
- End Station Name
- End Station Latitude
- End Station Longitude
- Bike ID
- User Type
- Bike share for all Trip

I removed the longitude and latitude variables alongside bike share for all trip as I don't use them in my analysis. I changed the birth year column from float to integer, removed nulls in certain columns, change start and end time to datetime dtype, created a day column to hold the day of week the ride took place and made day & gender columns to categorical.

## Summary of Findings
- Most of the rides were taken by subscribers as they occupy 91% in the dataset.
- We have more active people(those in prime; age 18 - 60) in the dataset.
- Rides were made mostly by male as they dominated the data by occupying 75% of all rides.
- Most of the rides are short duration rides.
- The major part of the trips took place oon work days; Monday to Friday.
- Subscribers engage trips far more than customers on every day of the week.
- Male typically rides moore than females every day of the week.
- Trip duration for each day of week in the dataset are majorly short(we can have longer trip duration).
- People within the age 20 - 65 spend less time on bike than people above 65.
- Subscribers within the age of 20 -65 spend less time on bike compared to customers.
- Females typically spend more time on rides than males though the difference is not large.

## Key Insights for Presentation
I mainly focus trips number of rides made on each day of the week. Then
trip duration with respect to user type and gender. Which ones spend more time rding around and which spend less time doing the same thing using three key visualizations that I merged together within a single figure.