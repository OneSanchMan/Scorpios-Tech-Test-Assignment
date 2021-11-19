Assume that the user is in churn if his/her last event has occurred at least a week ago.
Using the event data(export_api) for users with version 1.0.8 onwards and user data(users), segment each user who has not
churned yet, to one of the 3 clusters:
1. Users who are least likely to churn 0-25%
2. Users who are most likely to churn 75-100%
3. Other users - 25-75%

INPUT DATA
The data is stored on MongoDB NoSQL database called ‘data’ and can be accessed at analytics.adviseme.app:27017. There are
three collections in total:
  • “export_api” is a collection of documents that store events data
  • “users” is a collection of documents that store up-to-date user data
  • “script_data” is a collection that is not required in the task below
Please see the data definitions and events list here.

DELIVERABLES:
The solution should consist of:
  • One file with the results of the task that contains two fields:
    o amplitude_id - unique id of a user
    o The segment the user belongs to
• The code that was used for solution - link to GitHub or archived file
• A pdf file that describes the following points:
  o Why the proposed model is a good solution?
  o Your steps were taken to achieve the proposed solution
