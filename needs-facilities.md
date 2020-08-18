# Visit-counter for a Facilities Manager

## Scenario: Report visitor trends during a week of operation

Given the report of visitor is being maintained
  
When The data for a week is collected
  
Then analyse the data and display visitor trends.

## Scenario: Alert when seating capacity is full

Given : Visitors are entering the hospital.

When : The no of visitors is equal the seating capacity

Then : Alert-"Seating Capacity full" is sent to the Facilities manager.
