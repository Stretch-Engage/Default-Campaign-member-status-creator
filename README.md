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

1.  Open Salesforce **Setup**
2.  Go to **Custom Metadata Types**
3.  On the Metadata Type **Default Campaign Member Status**, click **Manage Records**
4.  Click **New**
ETC.

Example status \
![Example status ](.assets/exampleCustomMDTrecord.png)

## Custom Metadata Type

| Field Type     | Field Name | API Name    | Data Type | Example | Description                                     |
|----------------|------------|-------------|-----------|---------|-------------------------------------------------|
| Standard Field | Label as   | MasterLabel | Text(40)  |         | Descriptive Label of the campaign member status |
|                |            |             |           |         |                                                 |
|                |            |             |           |         |                                                 |


# Future potential improvments

TBD...

# Links or documentation

TBD...
