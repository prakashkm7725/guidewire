Credentials:

1.salesforce:
url: https://nousinfo6-dev-ed.my.salesforce.com/
username: nousinfo2022@gmail.com
password: Nous@1234
security token: f3MZIaGGHTgZ4sVSI6UdHVlB

2.amazon S3:
accountId: 993878080430
username: manuelg@nousinfo.com
password : :Mgmalayil@031991


Salesforce custom objects:

1. Claim__c
2. Activity__c
3. Checkset__c
4. ChecksetTemplate__c


system api cloudhub url: insurance-claim-management-sys-api.sg-s1.cloudhub.io
process api cloudhub url: insurance-claim-management-prcs-api.sg-s1.cloudhub.io


postman collection:
https://www.getpostman.com/collections/d8a46f905383f32dce40


To change the Salesforce account from Anypoint’s Runtime Manager, 
•	Go to runtime manager -> click on the application name -> settings
•	Settings -> Properties tab provide the values that you want to change along with the key and then click on Apply changes button.
    salesforce.username : <to your new username>
    salesforce.password : <to your password>
    salesforce.accessToken : <to your securityToken>