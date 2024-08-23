# Africa Malaria Incidence Analysis

## Overview
This repository contains a comprehensive analysis of malaria incidence across African countries, focusing on various aspects such as trends over time, correlation with prevention strategies, and the impact of sanitation and water services. The dataset includes information on malaria incidence, bed net usage, sanitation services, and population demographics.


## Dataset
The dataset used in this analysis is DatasetAfricaMalaria.csv, which includes the following columns:
* Country Name: Name of the country
* Year: Year of the record
* Incidence of malaria (per 1,000 population at risk): Rate of malaria incidence
* Malaria cases reported: Number of reported malaria cases
* Use of insecticide-treated bed nets (% of under-5 population): Percentage of under-5 population using bed nets
* People using safely managed sanitation services, rural (% of rural population): Percentage of rural population with access to safe sanitation services
* People using safely managed drinking water services, rural (% of rural population): Percentage of rural population with access to safe drinking water
* Rural population (% of total population): Percentage of total population residing in rural areas
* Urban population (% of total population): Percentage of total population residing in urban areas
* Rural population growth (annual %): Annual percentage growth of rural population
* Urban population growth (annual %): Annual percentage growth of urban population


## Code Overview
## Data Loading and Initial Assessment
* Loaded the dataset using pandas.
* Performed initial data exploration, including checking column names, data types, missing values, and duplicates.


## Data Cleaning
* Replaced missing values with 'Unknown'.
*	Converted relevant columns to numeric types for analysis.


## Analysis
*	Trend of Malaria Incidence: Analyzed the overall trend of malaria incidence over time.
*	Country with Highest Malaria Cases: Identified the country with the highest number of malaria cases.
*	Top 5 Countries with Highest Malaria Incidence: Listed the top 5 countries with the highest malaria incidence.
*	Year with Highest Global Average Malaria Incidence: Determined the year with the highest global average malaria incidence.
*	Correlation Analysis: Examined the correlation between bed net usage and malaria incidence.
*	Sanitation Improvement: Assessed improvements in rural sanitation services.
*	Rural vs. Urban Population: Compared rural and urban population distributions in top malaria-affected countries.
*	Bed Net Usage Over Time: Analyzed changes in bed net usage for the top 5 malaria-affected countries.


## Ghana-Specific Analysis
*	Conducted detailed analysis for Ghana, including:
*	Trend of malaria incidence
*	Change in number of malaria cases reported
*	Correlation between bed net usage and malaria incidence
*	Access to safely managed drinking water services and sanitation services
*	Rural vs. urban population distribution
*	Impact of rural population growth on malaria incidence
*	Trend of urban population growth and its correlation with malaria incidence
*	Year with highest malaria incidence and corresponding conditions


## Visualization
*	Malaria Incidence Trend: Line plot showing malaria incidence over time in Ghana.
*	Malaria Cases Reported: Bar plot depicting malaria cases reported over time.
*	Bed Net Usage vs. Malaria Incidence: Scatter plot illustrating the relationship between bed net usage and malaria incidence.
*	Access to Safely Managed Drinking Water Services: Line plot showing trends in access to safe drinking water services.
*	Access to Safely Managed Sanitation Services: Line plot depicting trends in access to sanitation services.
*	Rural vs Urban Population Distribution: Dual line plot comparing rural and urban population distributions.


## Conclusion
The analysis provides valuable insights into malaria incidence across Africa and specifically in Ghana. Key findings include:
1.	Overall Trend: There has been a notable fluctuation in malaria incidence over the years, with some countries showing significant improvements while others face persistent challenges.
2.	Country with Highest Cases: The country with the highest number of malaria cases reported varies, but trends indicate that certain regions consistently report higher incidence rates.
3.	Top Malaria-Affected Countries: The top 5 countries with the highest malaria incidence highlight regions where targeted prevention and treatment strategies are crucial.
4.	Prevention Strategies: The correlation analysis indicates that increased use of insecticide-treated bed nets is associated with reduced malaria incidence, though the strength of this correlation varies.
5.	Sanitation and Water Services: Improvements in rural sanitation and drinking water services are linked to better health outcomes, including reduced malaria incidence.
6.	Ghana-Specific Trends: In Ghana, malaria incidence shows varying trends over time, with correlations between bed net usage and incidence providing insights into the effectiveness of malaria prevention measures.

The data underscores the importance of continuous monitoring and targeted interventions in malaria prevention. 
By understanding these trends and correlations, stakeholders can better focus their efforts on effective strategies and resource allocation.

## Contributing
Feel free to fork the repository, create a pull request, or report issues. Contributions are welcome!

