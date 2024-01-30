# Orange-HRM-Project-

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application.

Application under test: https://opensource-demo.orangehrmlive.com/web/index.php/dashboard/index

API Documentation:

The final project will be split into 2 sections: Testing section and SQL section.

Tools used: Jira , zephyr 

Functional specifications : https://itfclasses.atlassian.net/jira/software/c/projects/MIN/boards/306

Functionalities in scope :

1.Admin Module,
	User management, 
	Job,
	Organization,
        Qualifications,
	Nationalities,
        Configuration,



1.1 Test planning 

The Test Plan is designed to describe all details of testing for the Admin module from the OrangeHRM application.
The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.

1.1.1 Roles assigned to the project and persons allocated : 
Minodora Bianca - Admin module 

1.1.2 Entry criteria defined 

Entry criteria:
smoke test passed (being the most basic type of test, this is a very important entry criteria in the process of testing)
testing environment is up and running

1.1.3 Exit criteria defined 

Exit criteria:
92% of tests are passed
no Critical issues have Open status
update tests are 100% passed (update tests will not generate other new issues that impact the application)

1.1.4 Test scope
Tests in scope: admin module to function at its max capacity without any error occurred
Tests not in scope: not applicable 


1.1.5 Risks detected

Risks: user data (permissions, user roles, sensitive data etc) might be impacted with update tests
Safari browser might have performance issues or compatibility issues
website doesn’t support 100 users


1.1.6 Evaluating entry criteria
The entry criterias defined in the Test Planning phase have been achieved and the test process can continue.

Testing the log in functionality

Verification log in 

Test Case 1: 	
    Description: Test login successfully
		
  Preliminary conditions: The user must be on the log in page
		
  Execution steps: 
    
  1. Enter valid user
  2. Enter valid password 
  3. Press the log in button 
     
   Test data: user valid:.... password valid:....
		Current results: log in succsefully
		Expected results: The user must be redirected to the home page 


  1.2 Test Monitoring and Control
  




