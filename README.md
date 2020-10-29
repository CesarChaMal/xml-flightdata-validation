# Flight data specification

## Introduction

The dataset contains a full list of aircraft movements for different aircraft. Some of these files contain flaws.
Find out which files are invalid, and identify the cause of failure for each invalid file.
You should spend a maximum of 1 hour for this task.

## Provided materials

`flightschedule.xsd` - a schema definition for the flightschedule dataset.
`flightschedule1-6.xml` - 6 data files

### Dataset description

#### Aircraft

Describes the general properties of the aircraft which the dataset belongs to.
Includes registration code, aircraft type, capacity (passengers) and the aircraft's owner.

#### Flights

Lists all flights in a specified time period.

id = Unique id for the flight
departure / arrival airport = Airport IATA code
plannedtime = Planned departure / arrival date and time in UTC
actualtime = Actual departure / arrival date and time in UTC
flighttime = Flight time in minutes
cargo dangerous = Flight contained dangerous cargo, eg. hazardous materials, Y=Yes, N=No
cargo weight = Total cargo weight in kilograms# xml-flightdata-validation.
# xml-flightdata-validation.
