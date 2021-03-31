## Ford GoBike Analysis
## by Sandy Ibrahim


## Introduction 
This is the last project in Udacity Data Analysis Advanced Track which we study how to use data visualization in data analysis.

## Dataset Overview
Bay Wheels is a regional public bicycle sharing system in California's San Francisco Bay Area.it is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States. It was established as Bay Area Bike Share in August 2013. As of January 2018, the Bay Wheels system had over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose. In June 2017 the system was officially re-launched as Ford GoBike in a partnership with Ford Motor Company. After Motivate's acquisition by Lyft, the system was renamed to Bay Wheels in June 2019. The system is expected to expand to 7,000 bicycles around 540 stations in San Francisco, Oakland, Berkeley, Emeryville, and San Jose.

In this project, we explore data related to bike bike share systems for San Francisco Bay Area in the United States on the month of February 2019. This document explores a dataset containing 183412 rows and 16 columns.



## Summary of observations

1- Changing start_time and end_time columns from object to datetime to be able to extract days of the week and months if needed.                 
2- Changing seconds to minutes of 'duration_sec' so it will be easy in comparison.                               
3- Creating a new column for age to see the impact of age on bike usage.     
4- Removing the missing &  Nan values from the data.

## Summary of Findings

1- The bike usage is mostly on weekdays not on weekends.                
2- The most bike usage is during the morning peak (7-10 AM) and the evening peak (4-7 PM).                           
3- Most of the riders are males.                    
4- Most riders are between 20 to 40 years.                       
5- Most riders are subscribers.                    
6- The top station of pickup a bike is "Market St at 10th St".


## Key Insights for Presentation
I focused on the usage of bike affected by age , gender , user type, time of day & weekdays. we found that the most riders are males subscribers renting the bikes on weekdays more than the weekends and during the morning or evening peak hours, therefore we assumed that the most bikes are rented by people for mobility to and from work.


