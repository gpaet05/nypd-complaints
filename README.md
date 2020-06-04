# Crimes Reported to the New York City Police Department

## Introduction

This dataset includes all valid felony, misdemeanor, and violation crimes reported to the New York City Police Department (NYPD) from xxxx-year to xxxx-year (TBD). The goal of my analysis is to xyz.

## Data Dictionary

| Field | Description |
| :--- | :--- |
| CMPLNT_NUM | Randomly generated persistent ID for each complaint  |
| ADDR_PCT_CD | The precinct in which the incident occurred |
| BORO | The name of the borough in which the incident occurred |
| CMPLNT_FR_DT | Exact date of occurrence for the reported event (or starting date of occurrence, if CMPLNT_TO_DT exists) |
| CMPLNT_FR_TM | Exact time of occurrence for the reported event (or starting time of occurrence, if CMPLNT_TO_TM exists) |
| CMPLNT_TO_DT | Ending date of occurrence for the reported event, if exact time of occurrence is unknown |
| CMPLNT_TO_TM | Ending time of occurrence for the reported event, if exact time of occurrence is unknown |
| CRM_ATPT_CPTD_CD | Indicator of whether crime was successfully completed or attempted, but failed or was interrupted prematurely |
| HADEVELOPT | Name of NYCHA housing development of occurrence, if applicable |
| HOUSING_PSA | Development Level Code |
| JURISDICTION_CODE | Jurisdiction responsible for incident. Either internal, like Police(0), Transit(1), and Housing(2); or external(3), like Correction, Port Authority, etc. |
| JURIS_DESC | Description of the jurisdiction code |
| KY_CD | Three digit offense classification code |
| LAW_CAT_CD | Level of offense: felony, misdemeanor, violation  |
| LOC_OF_OCCUR_DESC | Specific location of occurrence in or around the premises; inside, opposite of, front of, rear of |
| OFNS_DESC | Description of offense corresponding with key code |
| PARKS_NM | Name of NYC park, playground or greenspace of occurrence, if applicable (state parks are not included) |
| PATROL_BORO | The name of the patrol borough in which the incident occurred |
| PD_CD | Three digit internal classification code (more granular than Key Code) |
| PD_DESC | Description of internal classification corresponding with PD code (more granular than Offense Description) |
| PREM_TYP_DESC | Specific description of premises; grocery store, residence, street, etc. |
| RPT_DT | Date event was reported to police  |
| STATION_NAME | Transit station name |
| SUSP_AGE_GROUP | Suspect’s Age Group |
| SUSP_RACE | Suspect’s Race Description |
| SUSP_SEX | Suspect’s Sex Description |
| TRANSIT_DISTRICT | Transit district in which the offense occurred. |
| VIC_AGE_GROUP | Victim’s Age Group |
| VIC_RACE | Victim’s Race Description |
| VIC_SEX | Victim’s Sex Description |
| X_COORD_CD | X-coordinate for New York State Plane Coordinate System, Long Island Zone, NAD 83, units feet (FIPS 3104) |
| Y_COORD_CD | Y-coordinate for New York State Plane Coordinate System, Long Island Zone, NAD 83, units feet (FIPS 3104) |
| Latitude | Midblock Latitude coordinate for Global Coordinate System, WGS 1984, decimal degrees (EPSG 4326)  |
| Longitude | Midblock Longitude coordinate for Global Coordinate System, WGS 1984, decimal degrees (EPSG 4326) |

* To be edited. Will likely drop unused columns to save on space.

Keep writing more stuff here!

## Important Links

* [Final Report Notebook](report.ipynb)
* [EDA Notebook](eda.ipynb)
* [Link 1](http://www.google.com) - Some cool stuff
* [Link 2](http://www.google.com) - More cool stuff
* [Link 3](http://www.google.com) - Even more cool stuff
