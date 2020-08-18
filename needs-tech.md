# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter

Given foot-fall sensor at the door is working

When the server restarts

Then continue with the previous counter

Scenario: Reconcile counts if the sensor is offline for a while

Given foot fall sensor at the door is working

When The server is offline

Then one person can manually count the visitor until server is back

and update the count in server.
