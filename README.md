# Simple Campaign Member Status 

## Background

Salesforce does not have a standard way of changing and creating new default Campaign Member Statuses. 

## Deploy

You can use the quick installer here to deploy directly to your org. \
[![Deploy to salesforce](https://githubsfdeploy.herokuapp.com/resources/img/deploy.png)](https://githubsfdeploy.herokuapp.com/?owner=ehsky&repo=Default-Campaign-member-status-creator)

### Quick hands-on demo in Salesforce org

You can quickly spin up an org by clicking on the picture below. \
This will create a scratch org that you have access to for 1 day \
[![Demo scratch org](/.assets/deployDemo.png)](https://hosted-scratch.herokuapp.com/launch?template=https://github.com/ehsky/Default-Campaign-member-status-creator)

# How to set up a new default status

1.	Open Salesforce Setup
2.	Go to Custom Metadata Types
3.	On the Metadata Type Default Campaign Member Status, click Manage Records
4.	Current Campaign member statuses this package populated: ‘Attended’, ‘Deregistered’, ‘Invited’, ‘No-Show’ and ‘Registered’
5.	To add a new status Click New.
6.	Fill in Label, Default Campaign Member Status Name and Status Name
7.	Click Save
![image](https://user-images.githubusercontent.com/123372077/214292774-c5f755cc-e614-4bc5-ba34-fb6903acb7ad.png)


Example status \
![Example status ](.assets/exampleCustomMDTrecord.png)

## Custom Metadata Type  (Standard Field)

| Field Type     | Field Name | API Name    | Data Type | Example | Description                                     |
|----------------|------------|-------------|-----------|---------|-------------------------------------------------|
| Standard Field | Label      | MasterLabel | Text(40)  |         | Descriptive Label of the campaign member status |
|                |            |             |           |         |                                                 |
|                |            |             |           |         |                                                 |


## Custom Metadata Type (Custom Field)

| Field Type     | Field Name | API Name     | Data Type | Example | Description                                     |
|----------------|------------|------------- |-----------|---------|-------------------------------------------------|
| Custom Field   | Default    |IsDefault__c  |Checkbox   |         |                                                 |
| Custom Field   |Description |Description__c|Text(255)  |         |                                                 |
| Custom Field   |Has Responded|HasResponded__c|Checkbox |         |                                                 |
| Custom Field   |Remove Standard Status|RemoveStandardStatus__c|Checkbox|         |                                 |
| Custom Field   |Standard 'Sent' or 'Responded' Status|StandardSentOrRespondedStatus__c|Checkbox |         |        |                                     
| Custom Field   |Statues Name|StatuesName__c|Text(40) |         |                                               

# Future potential improvments

TBD...

# Links or documentation

Flow overview

The provided template flow is intended as a no-code deploy example of how this can be built. 
Your free to customize this the way you see fit.

![Screenshot 2023-01-24 at 14 42 39](https://user-images.githubusercontent.com/123372077/214310538-e939599d-b0c9-4961-b7ea-1d4420b10a7d.png)
TBD...
