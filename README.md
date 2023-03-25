# **Use Case**
<!-- Use Case (start) -->
This service is used to do one-time data migration for Contracts data from Cayenta to Salesforce
<!-- Use Case (end) -->

## **As a Data Source**

Cayenta will be a data source for this service, The data can be provided as csv file from a folder location or direct DB access

## **As a Data Destination**

Salesforce is a target environment for this service

## **Properties to Configure**
To use this service, configure properties such as credentials, configurations, etc.) in the properties file or in CloudHub from Runtime Manager > Manage Application > Properties. The sections that follow list example values.

# **SalesForce Connector Configuration**

+ sfdc.username `user.name@sfdc`
+ sfdc.password `StrongPassword123`
+ sfdc.securityToken `avsfwCUl7apQs56Xq2AKi3X`

## **SMTP Services Configuration**

+ smtp.host `smtp.gmail.com`
+ smtp.port `587`
+ smtp.user `email@example.com`
+ smtp.password `password`

## **Email Details**

+ mail.from `example@email.com`
+ mail.to `your@email.com`
+ mail.subject `Batch Job Finished Report`
​
<!-- Application Configuration (end) -->

# **API Calls**
<!-- API Calls (start) -->
There are no particular considerations for this template regarding API calls as the service will be triggered with file listner or scheduler (TBD)
<!-- API Calls (end) -->
