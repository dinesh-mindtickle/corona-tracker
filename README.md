# corona-tracker
**Goal:** To advise the general population and government about possible covid infected areas. 

**Process:** Gather data of infected person and storing it in a logical way which can be used to deduce possible infected people and areas.

One of the major issues with covid is that even if a person is not symptomatic, he/she can start spreading the disease without even knowing it. Hence, we need to get the travel history of the patient in an automatic way. 

## What data is needed:
1. Time Vs Coordinate 
2. Details of public transport the patient has taken
3. Details of public places patient has gone to


## How will we get the data:
**1. Time Vs Coordinate:**
Google timeline stores the location history. One can download the data in kml format with gives exact location of the user at a given time


**2. Details of public transport the patient has taken:**
By going through the SMSes, we might be able to get all of the public transport the patient has taken

**3. Details of public places patient has gone:**
		This can be taken out from the kml data exported
