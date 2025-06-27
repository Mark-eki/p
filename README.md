# 1. Introduction into the Business**
### 1.1 Understanding the Business**
##### At Jungle Ltd, we specialize in Transportation of goods and services. The company was started in 2010 by John Doe and has grown from a 3 vehicle business to a 100 vehicle operating business machinery. Our top of the line vehicles offer comfortable, luxurious and affordable transport from various places in the country. We pride ourselves on being on time and offering our clients the best experience
### 1.2 Business Problem**
##### With the success of the business, The C.E.O has decided its time to take its interest further by investing in another branch business of flying people to their destinations. To ensure taking our clients arrive faster and safer, The C.E.O decided to acquire fleet of airplanes for both private and commercial use. With no clue about how to run an airplane service, it has to be determined which are the best airplane to buy with the lowest risk of use
### 1.3 Purpose of Analysis and Objectives**
##### The purpose of this analysis is to use the dataset to come up with reasonable actionable intelligence about the aviation industry where our objective is to start a new business in the airline business.
## 1.4 Limitation of dataset**
##### We are operating under the assumption that the dataset is accurate with the required information required to make an informed decision
## 2.Data Understanding**
##### Here we are going to use the necessary instruments to read the data from the National Transport Safety Board (NTSB).
### 2.1 Here we look at what our data looks like
##### Our data has 88889 rows and 31 columns
##### The columns are
##### 
(['Event.Id', 'Investigation.Type', 'Accident.Number', 'Event.Date','Location', 'Country', 'Latitude', 'Longitude', 'Airport.Code','Airport.Name', 'Injury.Severity', 'Aircraft.damage','Aircraft.Category', 'Registration.Number', 'Make', 'Model','Amateur.Built', 'Number.of.Engines', 'Engine.Type', 'FAR.Description','Schedule', 'Purpose.of.flight', 'Air.carrier', 'Total.Fatal.Injuries','Total.Serious.Injuries', 'Total.Minor.Injuries', 'Total.Uninjured','Weather.Condition', 'Broad.phase.of.flight', 'Report.Status','Publication.Date']
### 2.1 Data statistics
##### The statistics for the original data are as follows

  Number.of.Engines 	Total.Fatal.Injuries 	Total.Serious.Injuries 	Total.Minor.Injuries 	Total.Uninjured
|count  |    82805.000000  |  77488.000000 	          76379.000000 	        76956.000000        	82977.000000
mean         1.146585 	        0.647855 	               0.279881 	            0.357061          	5.325440
std 	       0.446510 	        5.485960 	               1.544084 	            2.235625 	          27.913634
min 	       0.000000 	        0.000000 	               0.000000 	            0.000000          	0.000000
25% 	       1.000000 	        0.000000 	               0.000000 	            0.000000           	0.000000
50% 	       1.000000 	        0.000000               	 0.000000 	            0.000000 	          1.000000
75% 	       1.000000 	        0.000000 	               0.000000 	            0.000000 	          2.000000
max 	       8.000000 	        349.000000 	             161.000000 	          380.000000 	        699.000000
