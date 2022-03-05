# <p align = 'center'>Boston Crime Analysis</p>

Crime incident reports are provided by Boston Police Department (BPD) to document the initial details surrounding an incident to which BPD officers respond. This is a dataset containing records from the new crime incident report system, which includes a reduced set of fields focused on capturing the type of incident as well as when and where it occurred. Records in the new system begin in June of 2015. </br>

The Analyze Boston Data Exports posted now are the updated incident data from the Mark43 RMS Database which launched in September of 2019 and is complete through present with the exclusion of data that falls under MGL ch.41 s.98f. The 2019 data that was originally posted contained combined exports from the Intergraph RMS and the Mark43 RMS during 2019 but the Extract/Transfer/Load process was not updated during the transition. We are continuing work on producing the gap data from January 2019 to September 2019 from our legacy Intregraph RMS and will be publishing this as soon as the work is complete. </br>

The Data is collected from Kaggle: <a href = "https://data.boston.gov/dataset/crime-incident-reports-august-2015-to-date-source-new-system"> Link </a> </br>

# Data Defination

1. incident_num - Internal BPD report number
2. offense_code - Numerical code of offense description
3. Offense_Code_Group_Description - Internal categorization of offense_description
4. Offense_Description - Primary descriptor of incident
5. district - What district the crime was reported in
6. reporting_area - RA number associated with the where the crime was reported from.
7. shooting - Indicated a shooting took place.
8. occurred_on - Earliest date and time the incident could have taken place
9. UCR_Part - Universal Crime Reporting Part number (1,2, 3)
10. street - Street name the incident took place

# Results

1. Top 15 Areas with Highest Crime Rate in Boston -

<img src = "Images/Story 1.png"> <br>

From the above plot we can interpret that "Washington Street" has the highest number of Crime cases occured, so we can assume that it is the most unsafe place to live in. While, "Warren Street" has the least number of Crime Cases. <br>
 
 2. Average Cases V/s Total Number of Shooting Reported in Boston -

<img src = "Images/Story 2.png"> <br>

We can interpret from the graph that in "AUGUST", highest number of Shooting Cases occur followed by "JUNE" and "MAY". While in "September" has the highest Crime Cases Reported even though there are very less number of Shooting Cases occuring. <br>

 3. Top 10 Offenses in Boston -

<img src = "Images/Story 6.png"> <br>

From the above plot, we can interpret that highest number of Crime Rate  occured for "Personal Investigation" offense while the lowest crime rate occured during "Verbal Dispute". <br>

4. Top 15 Offenses That were Reported in Boston -

<img src = "Images/Story 8.png"> <br>

We could interpret that "Investigate Property" offense has the highest number of Shooting cases reported while "Residential Burglary" has the lowest number of Shooting cases Reported. <br>

5. Total Number of Crime Rate V/s Number of Crime Cases Reported in Boston -

<img src = "Images/Story 11.png"> <br>

We can interpret from the above graph that, "B2" district has the highest number of Crime Rates occured among other districts while "A15" has the lowest number of Crime Rates Occured and Reported at the same time. <br>

# Conclusion
