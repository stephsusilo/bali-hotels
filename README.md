# Data Collection & SQL Analysis | Bali Hotels | Booking.com
### SQL Project for ISBA 4715

## Project Objective
Booking.com wants to improve their customer experience by launching a new service to offer customers a helping hand in picking out the perfect hotel with our travel specialists. Instead of searching through filters and browsing through pages of hotels we want to test a new service that offers a personalised experience for each guest. Test this concept by curating a list of hotels for a given customer.


## Job Description
The job posting I selected is for a Business Intelligence internship at Tiket.com, Indonesia’s leading OTA company. The primary role of the job, as specified by the job description is to help on the task delivery of Business Intelligence and to understand the table relations in the Data Warehouse. This includes performing descriptive analysis, enhancing dashboard/query for data warehouse, and developing a deeper understanding of the ideal Business Intelligence Architecture in the OTA industry. This project explores data collection and analysis from the same industry as Tiket.com using Booking.com.


## Data
### Source
The data was collected by conducting a web scrape of Booking.com’s hotel listings in Bali.

### Characteristics
#### Tables & Views
* hotels
* subdistrict
* district
* hotel_rating_category
* avg_price_by_rating_category

## Notebooks
[Data Collection](data_collection.ipynb)
* Purpose: To build a dataset of hotels in Bali through web scraping on Booking.com

[SQL Analysis](sql_analysis.ipynb)
* Purpose: To perform descriptive analytics through exploratory queries (part 1) and solve a business problem (part 2)

## Future Improvements
Instead of only retrieving data from one date and for one guest I would have liked to scrape data from multiple dates to more accurately reflect hotel prices since price always varies for hotels depending on demand and seasons. With this type of data I would have more options to analyse patterns and trends from current, past, and future data. 
