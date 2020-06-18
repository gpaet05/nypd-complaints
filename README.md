# Crimes Reported to the New York City Police Department

## Introduction

This dataset includes all valid felony, misdemeanor, and violation crimes reported to the New York City Police Department (NYPD) in 2018. Each row in the dataset represents 1 complaint/crime. The goal of my analysis is to discover if there are any trends in criminal activity: focusing on time (seasonal and hourly), borough population, and victim and suspect makeup.

## Data Dictionary

| Field | Description |
| :--- | :--- |
| CMPLNT_NUM | Randomly generated persistent ID for each complaint  |
| BORO_NM | The name of the borough in which the incident occurred |
| CMPLNT_FR_DT | Exact date of occurrence for the reported event (or starting date of occurrence, if CMPLNT_TO_DT exists) |
| CMPLNT_FR_TM | Exact time of occurrence for the reported event (or starting time of occurrence, if CMPLNT_TO_TM exists) |
| JURIS_DESC | Description of the jurisdiction code |
| LAW_CAT_CD | Level of offense: felony, misdemeanor, violation  |
| OFNS_DESC | Description of offense corresponding with key code |
| PREM_TYP_DESC | Specific description of premises; grocery store, residence, street, etc. |
| SUSP_AGE_GROUP | Suspect’s Age Group |
| SUSP_RACE | Suspect’s Race Description |
| SUSP_SEX | Suspect’s Sex Description |
| VIC_AGE_GROUP | Victim’s Age Group |
| VIC_RACE | Victim’s Race Description |
| VIC_SEX | Victim’s Sex Description |
| CMPLNT_FR_DT_YEAR | Year of the occurrence for the reported event |

In the interest of file size space, I dropped 20+ columns from the [original dataset](https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i) and limited the records to the year 2018. The full dataset includes records from 2006 to 2019.

## Important Links

* [Final Report Notebook](report.ipynb)
* [EDA Notebook](eda.ipynb)
* [NYC Open Data](https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i) - Source data
* [NYPD](https://www1.nyc.gov/site/nypd/index.page) - Official website of the NYPD
