# Orange-HRM-Project-

<h3>The scope of the final project</h3>  ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application.

Application under test: [ORANGE HRM](https://opensource-demo.orangehrmlive.com/web/index.php/dashboard/index).

API Documentation:


Tools used: Jira , zephyr 

Functional specifications :[JIRA PROJECT MIN-BOARD](https://itfclasses.atlassian.net/jira/software/c/projects/MIN/boards/306)

Functionalities in scope :
	<ol>
  <li>Admin Module</li>
  <li>Job</li>
</ol>

Functionalities not in scope :
<ol>
  <li>Automation Testing</li>
  <li>Designing the user interface</li>
  <li>Fixing bugs</li>
</ol>

1.1 Test planning 

The Test Plan is designed to describe all details of testing for the Admin module from the OrangeHRM application.
The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.

1.1.1 <h4>Roles assigned to the project and persons allocated4</h4>
| Admin module  | Job |
| ------------- | ------------- |
| Minodora Bianca| Minodora Bianca |

1.1.2 Entry criteria :


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
     
   Test data: user valid / password valid /
		Current results: log in succsefully
		Expected results: The user must be redirected to the home page 


 1.2 Test Monitoring and Control

  
  
 1.3 Test Analysis
 
The testing process will be executed based on the above requirements for the Dependents module. The following test conditions were found:

Enter test conditions here
 

1.4 Test Design

Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are:

Test cases: -> Job, Job Title, Job add Button, Pay Grades, Employment status, Job Categories, Organization , Work shifts

The test cases with steps can be viewed here: [test_cases.pdf](https://github.com/Mino26/Orange-HRM-Project-/files/14165184/test_cases.pdf)

1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins.

here what needs to be ready for the test execution to begin:

Ensure that the test enviorment is set up, test data is prepared and all necessary test resources, including test script and tools are in place.

Verify that the system under test is stable and ready for testing.


1.6 Test Execution

Test cases are executed on the created test Cycle summary: [cycle_summary.pdf](https://github.com/Mino26/Orange-HRM-Project-/files/14165225/cycle_summary.pdf)

The complete bug reports can be found here:  [work-shift.bug.pdf](https://github.com/Mino26/Orange-HRM-Project-/files/14165265/work-shift.bug.pdf)

Work shifts -> bug 


1.7 Test Completion
Exit criteria was evaluated and passed

The traceability matrix was generated and can be found here: [Forward Traceability_5_2_2024.xlsx](https://github.com/Mino26/Orange-HRM-Project-/files/14165640/Forward.Traceability_5_2_2024.xlsx)

Test execution chart was generated

-> enter here test execution report :

MIN-6
Aligment of component is on the top of the page
FAIL

MIN-6
Aligment of component is on the top of the page
PASS

MIN-7
Expand/collapse button is in the top of the right corner
PASS

MIN-8
User name cell correctly displayed
PASS

MIN-13
Job Titles
PASS

MIN-13
Job Titles
PASS

MIN-13
Job Titles
PASS

MIN-13
Job Titles
PASS

MIN-14
Job Title add button
PASS

MIN-15
Pay grades
PASS

MIN-16
Pay grades
PASS

MIN-18
Pay grades
PASS


MIN-19
Employment status
PASS


MIN-20
Employment status
PASS


MIN-21
Job Categories
PASS

MIN-22
Job Categories
PASS








