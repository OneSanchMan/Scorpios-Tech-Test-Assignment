# TASK
Assume that the user is in churn if his/her last event has occurred at least a week ago.
Using the event data(export_api) for users with version 1.0.8 onwards and user data(users), segment each user who has not
churned yet, to one of the 3 clusters:
1. Users who are least likely to churn 0-25%
2. Users who are most likely to churn 75-100%
3. Other users - 25-75%

# INPUT DATA
The data is stored on MongoDB NoSQL database called ‘data’ and can be accessed at -------. 
There are three collections in total:
  1. “export_api” is a collection of documents that store events data
  2. “users” is a collection of documents that store up-to-date user data
  3. “script_data” is a collection that is not required in the task below
Please see the data definitions and events list here.

# DELIVERABLES:
The solution should consist of:
  1. One file with the results of the task that contains two fields:
     - amplitude_id - unique id of a user
     - The segment the user belongs to
  2. The code that was used for solution - link to GitHub or archived file
  3. A pdf file that describes the following points:
     - Why the proposed model is a good solution?
     - Your steps were taken to achieve the proposed solution
