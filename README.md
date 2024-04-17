# Problems
- I'm using the AWS SES service to send emails. I will be running multiple email campaigns to send different types of emails. I want to track the performance of each campaign and I would like to track by user like which user has opened the email and which has clicked on the email. The data should be sent to the API endpoint and from there data would be saved in the database.
  Solution: We can configure SNS topic in SES. SES will send every event detail to SNS topic and in SNS topic we can use api endpoint to get details. So SNS will send details to API endpoint and then we can save it to DB
- I'm using Spring Security and I want to use Basic auth for one endpoint and Bearer token for rest of the endpoints.
