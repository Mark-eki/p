#  Aviation Data Analysis for New Enterprise
## 1. Introduction
### 1.1 Understanding the Business
##### At Jungle Ltd, we specialize in Transportation of goods and services. The company was started in 2010 by John Doe and has grown from a 3 vehicle business to a 100 vehicle operating business . Our top of the line vehicles offer comfortable, luxurious and affordable transport from various places in the country. We pride ourselves on being on time and offering our clients the best experience
### 1.2 Business Problem
##### With the success of the business, The C.E.O has decided its time to take its interest further by investing in another branch business of flying people to their destinations. To ensure taking our clients arrive faster and safer, The C.E.O decided to acquire fleet of airplanes for both private and commercial use. With no clue about how to run an airplane service, it has to be determined which are the best airplane to buy with the lowest risk of use
### 1.3 Purpose of Analysis and Objectives
##### The purpose of this analysis is to use the dataset to come up with reasonable actionable intelligence about the aviation industry where our objective is to start a new business in the airline business.
## 1.4 Limitation of dataset
##### We are operating under the assumption that the dataset is accurate with the required information required to make an informed decision
## 2.Data Understanding
##### Here we are going to use the necessary instruments to read the data from the National Transport Safety Board (NTSB).
### 2.1 Here we look at what our data looks like
##### Our data has 88889 rows and 31 columns
##### The columns are
##### 
(['Event.Id', 'Investigation.Type', 'Accident.Number', 'Event.Date','Location', 'Country', 'Latitude', 'Longitude', 'Airport.Code','Airport.Name', 'Injury.Severity', 'Aircraft.damage','Aircraft.Category', 'Registration.Number', 'Make', 'Model','Amateur.Built', 'Number.of.Engines', 'Engine.Type', 'FAR.Description','Schedule', 'Purpose.of.flight', 'Air.carrier', 'Total.Fatal.Injuries','Total.Serious.Injuries', 'Total.Minor.Injuries', 'Total.Uninjured','Weather.Condition', 'Broad.phase.of.flight', 'Report.Status','Publication.Date']
### 2.1 Data statistics
##### The statistics for the original data are as follows

| Statistic | Number of Engines | Total Fatal Injuries | Total Serious Injuries | Total Minor Injuries | Total Uninjured |
|-----------|-------------------|----------------------| ---------------------- | -------------------- | --------------- |
| Count     | 82805.0000        |    77488.000000      |  76379.000000  	|  76956.000000        |  82977.000000
| Mean      | 1.146585          |    0.647855          |    0.279881            |   0.357061           |   5.325440
| Std dev   | 0.446510          |    5.485960 	       |    1.544084    	|   2.235625           |  27.913634
| Min       | 0.000000          |    0.000000          |    0.000000            |   0.000000           |   0.000000
| 25%       | 1.000000          |    0.000000          |    0.000000            |   0.000000           |   0.000000
| 50%       | 1.000000          |    0.000000          |    0.000000            |   0.000000           |   1.000000
| 75%       | 1.000000          |    0.000000          |    0.000000            |   0.000000           |   2.000000
| Max       | 8,000000          |  349.000000          |  161.000000            | 380.000000           | 699.000000

### 2.2 Data Quality
##### Our Data included some missing values in our columns which we are supposed to deal with before proceeding to analyse our data. 
### 2.3 Data analysis
#####  Here we are going to use some key columns to analyse our data mainly
##### 1. Amateur built
##### 2. Make
##### 3. Aircraft Damage
##### 4. Total Fatal Injuries
##### 5. Number of Engines
##### 6. Engine Type
##### 7. Weather condition
## Tableau Dashboard**
##### Visualisatons can be found through https://public.tableau.com/app/profile/mark.muriithi6051/viz/tableauonnewAviatiandataanalysis/Dashboard1?publish=yes
## 3.Summary
##### 1. Multiple engine plane are safer to use beacuse they have low fatalities and accident
##### 2. Prioritise getting the planes with latest technology
##### 3. Rigorius training and retraining of pilots in case of emergency like failure of instruments
##### In conclusion, more information is required like size of plane, weight etc for further analysis and a more informed analysis.


