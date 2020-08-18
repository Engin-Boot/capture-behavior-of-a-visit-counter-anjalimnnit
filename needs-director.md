# Visit-counter for a Director

## Scenario: Show patient visits during working days and holidays

Given A person visits the hospital,

the entry card issuer issues separate card for the visitor and attendant.

When a person enters through the sensor

Then increament the visitor count by 1 for each card.

## Scenario: Compute parking slots to reserve for visiting specialists

Given Specialist visits the hospital and has planned visit beforehand

When Specialist enters the parking

Then a space is already reserved for parking.
