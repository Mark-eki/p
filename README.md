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
#####  #   Column                  Non-Null  Dtype  
---  ------                  --------------  -----  
 0   Event.Id                 non-null  object 
 1   Investigation.Type       non-null  object 
 2   Accident.Number          non-null  object 
 3   Event.Date               non-null  object 
 4   Location                 non-null  object 
 5   Country                  non-null  object 
 6   Latitude                 non-null  object 
 7   Longitude                non-null  object 
 8   Airport.Code             non-null  object 
 9   Airport.Name             non-null  object 
 10  Injury.Severity          non-null  object 
 11  Aircraft.damage          non-null  object 
 12  Aircraft.Category        non-null  object 
 13  Registration.Number      non-null  object 
 14  Make                     non-null  object 
 15  Model                    non-null  object 
 16  Amateur.Built            non-null  object 
 17  Number.of.Engines        non-null  float64
 18  Engine.Type              non-null  object 
 19  FAR.Description         32023 non-null  object 
 20  Schedule                12582 non-null  object 
 21  Purpose.of.flight       82697 non-null  object 
 22  Air.carrier             16648 non-null  object 
 23  Total.Fatal.Injuries    77488 non-null  float64
 24  Total.Serious.Injuries  76379 non-null  float64
 25  Total.Minor.Injuries    76956 non-null  float64
 26  Total.Uninjured         82977 non-null  float64
 27  Weather.Condition       84397 non-null  object 
 28  Broad.phase.of.flight   61724 non-null  object 
 29  Report.Status           82505 non-null  object 
 30  Publication.Date        75118 non-null  object 
