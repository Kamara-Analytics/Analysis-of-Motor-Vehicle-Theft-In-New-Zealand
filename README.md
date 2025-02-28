# Analysis of Motor Vehicle Theft In New Zealand
## The Data Immersed Emerald Cohort Excel Capstone Project

### Content
- [Project Overview](#Project-Overview)
- [Objectives](#Objectives)
- [Dataset and Column Description](#Dataset-and-Column-Description)
- [Data Transformation Process](#Data-Transformation-Process)
- [Key Insights](#Key-Insights)
- [Recommendations for Crime Prevention](#Recommendations-for-Crime-Prevention)
- [Next Steps](#Next-Steps)
   
### Project Overview
Motor vehicle theft remains a significant problem in New Zealand, impacting individuals, businesses, and law enforcement. Without a strong, data-driven approach, it’s difficult to pinpoint high-risk areas, understand the key factors behind thefts, or develop effective prevention strategies. The lack of a centralized system to track and analyze theft patterns makes it harder for decision-makers to allocate resources efficiently, anticipate trends, and take targeted actions to reduce vehicle-related crime.

### Objectives

The Motor Vehicle Theft Analysis Project aims to:
#### Identify Theft Trends:
- Analyze historical and real-time data to detect patterns in vehicle thefts, such as seasonal variations, frequency, and geographic distribution.
#### Assess Risk Factors: 
- Examine variables like vehicle type, theft location, time of occurrence, and socio-economic conditions to determine what influences theft rates.
#### Improve Crime Prevention Strategies: 
- Provide data-driven insights to law enforcement and policymakers for better resource allocation, targeted patrolling, and policy adjustments.
#### Enhance Public Awareness: 
- Inform vehicle owners, businesses, and insurance companies about high-risk areas and preventive measures to reduce theft risk.
#### Support Decision-Making: 
- Enable data visualization and interactive analytics for law enforcement agencies, helping them make informed strategic decisions to combat vehicle theft.
### Dataset and Column Description
The dataset consists of three key tables:
##### Stolen Vehicles: 
- Contains details about stolen vehicles, including ID, type, color, theft date, and location.
##### Make Details: 
- Holds information on vehicle manufacturers (make_id, make_name, make_type).
##### Locations: 
- Includes geographic and demographic data (location_id, region, population, density).
#### Columns Description;
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
### Data Transformation Process
- Merged the three datasets provided into one using index-match.
- Formatted each column to their appropriate data format.
- Checked for duplicates and none was found.
- Filled blanks in the vehicle_desc column with “Unknown”. Made 26 replacements.
- Filled blanks in the vehicle_types column with “Unknown”. Made 26 replacements.
- Filled blanks in the model_ID column with “Unknown”. Made 15 replacements.
- Filled blanks in the model_year column with “Unknown”. Made 15 replacements.
- Inserted “Vehicle Age” column using the formula; =YEAR(today()) – D2 (model_year). Pasted this new column as values, filled the blanks with “0”, made 15 replacements in the process.
### Key Insights 
- Over the course of 2021 & 2022, I've observed that most thefts occur during the first quarter. With a significant spike in the month of March.
- Regions with large population are generally at a higher risk of vehicle theft than regions with smaller population and density.
- Standard vehicles like station wagons and saloons are at a higher risk of theft than luxury vehicles like convertibles and sports cars. 
- Silver and white vehicles are at a higher theft risk than other vehicle colours.
### Recommendations for Crime Prevention
#### For Law Enforcement: 
- Increase patrols, CCTV surveillance , License Plate Recognition in high risk locations.
#### For Vehicle Owners:
- Use steering locks, GPS tracking, garage parking
#### For Policymakers:
- Stricter regulations on secondhand car parts sales, incentives for anti-theft technology. 
#### Next Steps:
- Continue monitoring theft trends.
- Strengthen collaboration among law enforcement, insurers, and policymakers against vehicle theft and related crime.
- Conduct more public awareness campaigns for vehicle theft in all the regions. 









