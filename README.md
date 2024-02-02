# Tableau_Excel_Influenza_staff_deployment
This repository features a Tableau dashboard and Excel processes designed for a U.S. medical staff agency. Specializing in providing temporary workers to clinics and hospitals as required, the data analysis presented here aids in preparing for the upcoming influenza season in 2018, a period marked by increased demand for medical staff. The findings delve into influenza trends in the United States, offering insights to proactively plan for staffing requirements. 

## Project Overview
### Motivation
The United States has an influenza season where more people than usual suffer from the flu. Some people, particularly those in vulnerable populations, develop serious complications and end up in the hospital. Hospitals and clinics need additional staff to adequately treat these extra patients.
### Objective
Determine when to send staff, and how many, to each state. 
### Scope
The agency covers all hospitals in each of the 50 states of the United States, and the project will plan for the 2018 influenza season.
## Datasets overview
* Mortality data: The Centers for Disease Control and Prevention (CDC) provides this administrative data. It contains monthly flu death counts in the US from 2009 to 2017. Counts are broken into two categories: state and age.
* Census data: The US Census Bureau provides this survey data. It contains demographic data for states including gender and age groups in the US from 2009 to 2017.

## Tableau dashboard
Following the implementation of Excel processes, I used Tableau to craft a compelling [dashboard](https://public.tableau.com/app/profile/nadia.ordonez/viz/PreparingforthefluintheUS/FluseasonUS?publish=yes). This dynamic visualization not only conveys my findings but also serves as robust support for the recommendations outlined in the medical staff deployment plan. Within Tableau, I utilized maps to illustrate flu death counts, forecasted deaths for 2018, and seamlessly integrated individual graphs using dashboards and story features for a comprehensive presentation. 

## Excel processes
I conducted data cleaning, consistency checks, and basic statistical analyses on the provided datasets. Prior to merging the two datasets, I pivoted the data at the state level and aligned age group information. Subsequently, I established a combined key to streamline the data mapping process. The integration was achieved using the `VLOOKUP` option, enabling the generation of death ratios by comparing death rates to population sizes per age group. For a detailed overview of the Excel processes, you can access the summary [here](https://docs.google.com/spreadsheets/d/1GHsGFBj2SdNdM0KWYc_ctxUAzaWQg4dB/edit?usp=drive_link&ouid=100495170560300906732&rtpof=true&sd=true). 
 
## Medical staff deployment recommendations for the 2018 flu season 
* Deploy extra medical staff to states with more than 500 deaths per year. Prioritazing states with the highest flu mortality (more than 2000 deaths per year).
* Inmediatly mobilize medical staff as the flu season reaches its peak at the onset of 2018, persisting until approximately April. Also, in October, it is imperative to redeploy medical staff. 
                                                                                                          
## Project timeline
This data analysis project was completed within 10 days, using Tableau for dashboard visualization and Excel for data analysis. An [interim report](Interim_report.pdf) document was also generated.  
