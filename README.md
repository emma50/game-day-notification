*An NBA game notification alert system*

This system uses the following aws services and resources
1. AWS SNS - This is a notification service which we used to send notifications to our email address.
2. AWS Lambda - This is a serverless service that manages infrAastructure for us automatically. This communicates with AWS SNS. We write our code and tell it what to do, but we don't care how it does it.
3. AWS EventBridge - This is used to trigger our lamba function when an event occurs. It uses the concept of cron jobs (Performing tasks at intervals).
