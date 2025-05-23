# AIRBNB-NEWYORK-2019

## OVERVIEW


This dataset contains detailed information about Airbnb listings in New York City as of 2019.
It includes pricing, location, host details, room types, availability, and customer
reviews—ideal for market analysis, real estate insights, and pricing strategy research

## Data sources



The primary source of data used here is AB-NYC-2019.CSV and this is an open source data that can be freely downloaded from an open source online such as kaggle or any other data repository site


## Dataset Details

Filename : AB_NYC_2019.csv

Size: 2MB

Rows: 48,895

 Column: 16


 Features
| Column | Description |
|--------|------------|
| `id` | Unique listing identifier |
| `name` | Listing title/description |
| `host_id` | Unique host identifier |
| `host_name` | Name of the host |
| `neighbourhood_group` | Borough (Manhattan, Brooklyn, etc.) |
| `neighbourhood` | Neighborhood name |
| `latitude` / `longitude` | Geographic coordinates |
| `room_type` | Entire home, Private room, or Shared room |
| `price` | Nightly price (USD) |
| `minimum_nights` | Minimum required stay |
| `number_of_reviews` | Total reviews received |
| `last_review` | Date of most recent review |
| `reviews_per_month` | Average review frequency |
| `calculated_host_listings_count` | Total listings per host
| `availability_365` | Days available per year 




## TOOLS USED


Microsoft Excel for data cleaning,Analysis

SQL for structured query language for querying of data

POWERBI for data visualisation

GITHUB for portfolio building









## DATA CLEANING AND PREPARATION

in the initial phase of the data cleaning and preparations,we perform the following actions

1.Data loading

2.handling missing variables

3.Data cleaning and formatting

4.Creating additional numeric column



### Explanatory data Analysis


The EDA process involves analyzing the AIRBNB data to understand the distribution of variables,identify patterns and trends ,detect potential issues and answer key question

1. What is the average availability of listing throughout the year by room type
   
3. what is price distribution by roomtype
   
5. what is price distribution by hostname
   
7. what is the minimum night by host name


## Key Insights (Sample Analysis)
### 1. Price Trends
- Most Expensive Borough: Manhattan ($196 avg/night)
- Most Affordable: Staten Island ($62 avg/night)
- Top 3 Priciest Neighborhoods:
1. Midtown (Manhattan)
2. Financial District (Manhattan)
3. Williamsburg (Brooklyn)


### 2. Host Behaviour

- 72% of hosts manage only **1 property**.

- **Top host (ID `219517`)** controls **327 listings** (likely a property management
company).
### **3. Room Types**
- **52%** of listings are **entire homes/apartments**.
- **Private  rooms** dominate in Brooklyn (45% of listings).

### 4.Demand 
-listing with high review/month are concerntrated in williamsburg and east village

### statistical  highlights
average price = $152.72
most common room type = Entire home(52%)

Recommendations
### For Hosts
-Manhattan hosts:highlight amenities to justify premium pricing
-Brooklyn hosts: target budget travelers with private rooms

### For travelers
-budget stays:opt for queens or staten island
-long stay:filter for listing with minimum nights <7


### For investors
-Focus on williamsburg and hells kitchen for high demand areas


## Limitations
1. Temporal data
-Data from 2019,post-pandemic trends may differ

2. Missing Metrics

-no square footage or eaact occupancy rates

3.Bias
-superhosts may be overrepresented due to higher review visibiity.


