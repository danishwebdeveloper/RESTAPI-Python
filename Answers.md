## Technical Support Engineer

 1- Question One: Add New Feature
* I would recommend creating a News Channel directly from the Content area of their Staffbase Administrator login for the imaginary customer that wants to display their news on the app. Moreover, the Staffbase API provides interaction with the News section, in addition to utilizing the Staffbase GUI to manually create new Channels and Posts. Create new channels and publish new content using the API.

* The Staffbase technique for Automatic CSV Imports could very likely be utilized to automatically update the News portion of their app, not just for onboarding new users, if their preexisting system generates news daily and they do not want to manually update it each day. I'd assist them in setting up the Automatic CSV Import to create fresh articles to their New Channel or Channels automatically.



2- Question two: Mapping Issues & Solution
* Customer attempting to setting up an Automatic CSV file is almost very close, but while mapping profile-field:firstName,profile-field:lastName,profile-field:position,eMail they are missing the important field a unique **externalID** as clearly written in the Automatic CSV Import guide.

* As I was approaching the problem, I studied the Automatic CSV Import instructions carefully, as well as the other documentation on the Staffbase support and developer portals, specifically the CSV File Examples provided by Staffbase. It became clear to me that they were missing a unique externalID. 

* I follow the step according to the instruction that every user needs an unique identifier that will be used as an external ID in Staffbase.” I would instruct the customer to add that column to their CSV file and to update the mapping accordingly and gets the desired result.
