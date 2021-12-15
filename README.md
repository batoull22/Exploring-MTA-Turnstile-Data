# Exploring-MTA-Turnstile-Data


## Introduction
This is the first project for the T5 Data Science Bootcamp, which is an exploratory data analysis of the MTA turnstile data set using SQL paired with Python and its libraries Pandas, NumPy, Matplotlib, and seaborn.

This exploratory analysis supports MTA turnstile's sanitizing company to help them improve their work schedule by estimating the number of sanitizing tours each station needs per day, based on their needs, with the busiest station requiring more than once a day. As I work on this issue, I will answer the questions below. 
><li>What are the most active stations?</li>
><li>What are the most active times for each station?</li>
><li>What are the most active days of the week?</li>
><li>What is the best schedule for the company?</li>

## About MTA: 

The Metropolitan Transportation Authority is North America's largest transportation network, serving a population of 15.3 million people across a 5,000-square-mile travel area surrounding New York City through Long Island, southeastern New York State, and Connecticut.

The MTA network comprises the nation’s largest bus fleet and more subway and commuter rail cars than all other U.S. transit systems combined. The MTA's operating agencies are MTA New York City Transit, MTA Bus, Long Island Rail Road, Metro-North Railroad, and MTA Bridges and Tunnels.

## MTA Turnstile Data:
Data obtained from http://web.mta.info/developers/turnstile.html.

## Field Description:

| Field Name | Description                                                                     |
|------------|---------------------------------------------------------------------------------|
| C/A        | Control Area (A002)                                                             |
| UNIT       | Remote Unit for a station (R051)                                                |
| SCP        | Subunit Channel Position represents an specific address for a device (02-00-00) |
| STATION    | Represents the station name the device is located at                            |
| LINENAME   | Represents all train lines that can be boarded at this station                  |
| DIVISION   | Represents the Line originally the station belonged to BMT, IRT, or IND         |
| DATE       | Represents the date (MM-DD-YY)                                                  |
| TIME       | Represents the time (hh:mm:ss) for a scheduled audit event                      |
| DESC       | Represent the "REGULAR" scheduled audit event (Normally occurs every 4 hours)   |
| ENTRIES    | The comulative entry register value for a device                                |
| EXITS      | The cumulative exit register value for a device                                 |


## Example:

The data below shows the entry/exit register values for one turnstile at control area (A002) from 09/27/14 at 00:00 hours to 09/29/14 at 00:00 hours

## Tools:
<li>SqLlit </li> 
<li>Aqlalchemy</li>
<li>Jupyter Notebook</li>
<li>Python</li>
<li>Pandas</li>
<li>numpy</li>
<li>Matplotlib</li>
<li>Seaborn</li>

## Deliverables:

Presentation describing our findings and recommendations.

EDA Analysis using python 

