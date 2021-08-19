# Assignment_RestAssured
This is Rest Assured Automation Framework 

In this Test Framework, I have used RestAssured library for Automating API.

I am using TestNG framework along with Maven build tool and using Extent Report for generating Report You will find the report under HTML Reports Folder.
After Tests are finished it will automatically generate the Report in that folder. I have tried to automate the get, Post and Put call in the framework.

For Get - 
1. First test is to get all the user in the list and verify the user and status code 
2. Second test is to get the 1111 -id user and verify the status code and first and last name
3. Third test is to check the invalid user - Get the call for 7777 -id and verifying the the bad call status code i.e 404
4. Fourth test is to create a new user and for that i am creating an JSON object and putting the value inside that and verifying the status code - i.e 201
5. Fifth test is to update the new user and for that i am using put command and verifing the status code i.e 200
 
How to Run the Tests from command prompt
1. Open the command prompt
2. use this command - mvn install
3. It will start running the Tests

Regards
