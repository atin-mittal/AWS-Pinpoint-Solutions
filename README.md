# AWS-Pinpoint-Solutions
-------------------------

### API to Send SMS and Email via Pinpoint
Users often face challenges in integrating communication channels with their applications which requires effort from development team. This solution will deploy the API's for SMS and Email comunication via Pinpoint and user can call the API directly for transactional communication.

Prerequisites:-
- Pinpoint Project needs to be setup
- SMS/Email channels should be enabled
- Upgrade the account from sandbox to production by raising a case to AWS support
- For SMS (India), DLT process has to be completed

This solution will deploy the following resources:-
- API Gateway
- Lambda for SMS
- Lambda for Email
- API Key and Usage plan
- Service permissions

![](/images/sms-email-api.jpg)

#### AWS CloudFormation Link
[CF Template](cloudformation/pinpoint-sms-email-api.yaml)
