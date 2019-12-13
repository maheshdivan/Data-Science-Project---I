# Data Science Project - I
Data Science Project repo
 
Zohna Jones, Yafreisi Gonzalez, Mahesh D Nair

Objective: Analyze delays for 3 airport per airline for 3 years

Hypothesis: Flight delays are mainly caused by weather

Questions: 
Which airport/airline has most total delays?
Which airport/airline is most reliable?
What is the major cause for airline delays?
Is there any direct relation between departure delay and factors causing delays?

Data: Flight Delay data for American & Delta Airlines for area airports: 
John F. Kennedy International Airport (JFK), Laguardia Airport (LGA), Newark Liberty International Airport(EWR) for 2017, 2018, 2019

Data Source: Bureau of Transportation Statistics 

Findings: 
Airport with most delays: LGA | Airport with least delays: EWR 
Major cause for delays: Varies by airline/airport (Details in coming slides)
Most reliable airline: American Airlines at JFK,EWR, & LGA 
Relational findings: Direct relations between delays and the delay causing factors (using initial analysis)

 
Four main categories of Jupyter Notebooks  *
1. Airport & Delay Analysis: American & Delta at JFK, LGA, EWR
   Removed the heading and unwanted columns and grouped data by date and destination to arrive at date of delay and delay causing    reason 
2. Comparison Analysis of American vs. Delta 
   Consolidated all data between LGA,JFK and EWR for American and Delta to find out the most reliable and least reliable airport
3. Hypothesis from Airport Analyses
   Defined a null hypothesis and plotted delay in minutes against all delay causing reasons to find direction relation (straight      line) and performed Ptest to check null hypothesis
4. Mapping flight statistics  
  Combined all airports data by American and Delta and plotted Donut chart to show % delays and shown delay on Google maps on       click on destinations (LGA, EWR and JFK)

