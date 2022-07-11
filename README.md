# RestAssuredFreeNow
Automation scripts for Freenow RestAPI task
Backend Test - I have implemented Automation Cucumber BDD framework,JUnit,Rest assured API and Maven build management tool and Java languages with 
Selenium automation tool.

Cucumber framework is scenario based tool so we can write the test steps/scenarios in Feature file. 
The advantages of this framework its easy to use, maintanance and reusable.

Three important files 
Feature (Creating the scenarios)
Step definitions(Java automation scripts) 
Test Runner(to drive the execution)

Please find the below validations using automation scripts
Search users for Samantha validate the posts and comments
	Get API Response users
	Search samantha user and get user id from the response
	Get API Response -Posts for the user id
	Get the user id and search in the Posts Response
	Get API Response "comments" for the post id
	Get the post id and search in the comments Response
	Verify email format in comments section for each post id.
  
Executed the automation suite locally and deployed the suite into circleci server, its executed successfully.
