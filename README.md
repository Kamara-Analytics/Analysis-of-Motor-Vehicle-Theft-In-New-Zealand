# Analysis of Motor Vehicle Theft In New Zealand
## The Data Immersed Emerald Cohort Excel Capstone Project
### Project Overview
Motor vehicle theft remains a significant problem in New Zealand, impacting individuals, businesses, and law enforcement. Without a strong, data-driven approach, it’s difficult to pinpoint high-risk areas, understand the key factors behind thefts, or develop effective prevention strategies. The lack of a centralized system to track and analyze theft patterns makes it harder for decision-makers to allocate resources efficiently, anticipate trends, and take targeted actions to reduce vehicle-related crime.

### Major Objectives

The Motor Vehicle Theft Analysis Project aims to:
#### - Identify Theft Trends:
Analyze historical and real-time data to detect patterns in vehicle thefts, such as seasonal variations, frequency, and geographic distribution.
#### -	Assess Risk Factors: 
Examine variables like vehicle type, theft location, time of occurrence, and socio-economic conditions to determine what influences theft rates.
#### -	Improve Crime Prevention Strategies: 
Provide data-driven insights to law enforcement and policymakers for better resource allocation, targeted patrolling, and policy adjustments.
#### -	Enhance Public Awareness: 
Inform vehicle owners, businesses, and insurance companies about high-risk areas and preventive measures to reduce theft risk.
#### -	Support Decision-Making: 
Enable data visualization and interactive analytics for law enforcement agencies, helping them make informed strategic decisions to combat vehicle theft.
### Dataset Description
The dataset consists of three key tables:
#### - Stolen Vehicles: 
Contains details about stolen vehicles, including ID, type, color, theft date, and location.
#### - Make Details: 
Holds information on vehicle manufacturers (make_id, make_name, make_type).
#### - Locations: 
Includes geographic and demographic data (location_id, region, population, density).
### Columns Description;
- Vehicle_id: Unique identifier for each stolen vehicle.
- Vehicle_type: Category of the vehicle (e.g., sports car, hatchback, trailer, etc.).
- Make_id: Unique ID linking to vehicle manufacturer details.
- Model_year: Year the vehicle was manufactured.
- Vehicle_desc: Description of vehicle.
- Color: Color of the stolen vehicle.
- Date_stolen: Date the theft was reported.
- Location_id: Unique identifier linking to geographic details.
- Make_name: Name of the vehicle manufacturer.
- Make_type: Type of vehicle (Standard or luxury)
- Region: The region in New Zealand where the theft occurred.
- Country: Country of theft (all "New Zealand").
- Population: Population of the region.
- Density: Population density of the region.
### Data transformation Process
- Merged the three datasets provided into one using index-match.
- Formatted each column to their appropriate data format.
- Checked for duplicates and none was found.
- Filled blanks in the vehicle_desc column with “Unknown”. Made 26 replacements.
- Filled blanks in the vehicle_types column with “Unknown”. Made 26 replacements.
- Filled blanks in the model_ID column with “Unknown”. Made 15 replacements.
- Filled blanks in the model_year column with “Unknown”. Made 15 replacements.
- Inserted “Vehicle Age” column using the formula; =YEAR(today()) – D2 (model_year). Pasted this new column as values, filled the blanks with “0”, made 15 replacements in the process.
### Pivot Tables
- Theft by Region (Region in rows, count of vehicle ID in values).
- Theft by vehicle type (vehicle_type in rows, count of vehicle ID in values).
- Theft by month (months (date stolen) in rows, count of vehicle ID in values).
- Theft by Region and population (Region in rows, count of vehicle ID and max of population in values).
- Theft by make type (make type in rows, count of vehicle ID in values).
- Theft by vehicle color (color in rows, count of vehicle ID in values).
- Theft by make name (make_name in rows, count of vehicle ID in values).
- Total number of vehicles stolen (count of vehicle ID in rows)
- Calculated the average age of stolen vehicles using a pivot table. Rounded the values to zero decimal places.
  
### Dashboard Structure

#### KPIs
- Total number of thefts: 4553
- Highest risk region: Auckland
- Most Stolen vehicle Type: Station wagon
- Peak theft month: March
- Average age of stolen vehicles: 20 yrs

#### Charts
Inserted charts for:
- theft by month (line chart)
- theft by make type (Pie chart)
- theft by region (bar chart)
- 5 stolen vehicle types (bar chart)
- top 7 stolen vehicle colors (column chart)

Slicers
Inserted slicers for quarters(date_stolen) and region.









