# Testing Project for Emag

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application
Application under test: Emag. <br> <br>
Tools used: Jira, Zephyr Squad. 

## Functional specifications:
The below stories were created in Jira and describe the functional specifications of the "Login" module, for which the final project is performed upon. 

![Story 1 - Github](https://github.com/OGeorgeDan/Manual_Testing_Jira/assets/149089987/592ddba8-0603-4b68-a4c8-a1659be6cd18)

Here you can find the release that was created for this project:

![Release Jira](https://github.com/OGeorgeDan/Manual_Testing_Jira/assets/149089987/5003e122-c758-4bae-baf1-62741c560719)


## Testing process
The test process was performed based on the standard test process as described below.

### 1.1 Test planning <br>
The Test Plan is designed to describe all details of testing for the login module for the Emag application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here <br>

(inserati link catre documentul cu planul de testare)

#### *1.1.1. Roles asigned to the project and persons allocated*

| USER | Role assigned | 
| ---- | -------------- |
| Olteanu Dan-George | Tester |

#### *1.1.2 Entry criteria defined*
+ Business requirements have been met.
+ Roles have been allocated.
+ Testing environment is up and running.

#### *1.1.3 Exit criteria defined*
+ All the test cases have been executed.
+ No critical issues have open status.
+ Tests are 90% passed (updated tests will not generate other new issues that impact the application).

#### *1.1.4 Test scope*
Tests in scope:
These tests will verify the:
+ login and create a new account functionality and wil also cover reseting the password.
+ the functionality of adding a new card to the account.
+ the functionality of filling a repairing form. 

> These tests will be made only on browser.

The types and techniques that will be used are:
+ Functional Testing
+ Usability Testing
+ Equivalence Partitioning
+ Boundary Value Analysis
+ Decision Tables
+ Positive/Negative Testing <br>
> Any other techniques that will be necessary will be applied accordingly. 

#### *1.1.5 Risks detected*
Project risks:
+ ***No project risks have been identified yet.*** TBA

Product risks:
+ ***No product risks have been identified yet.*** TBA

#### *1.1.6 Evaluating entry criteria*
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

### 1.2 Test Monitoring and Control <br>
Monitoring and control is a continuous phase that is being done with the purpose of monitoring the project developement and in order to identify any new projects risks that were not identified initially during the planning phase. It was done through generating period test metric reports that showed the progress of the testing process, as seen in the example below:

![Test Metric 1](https://github.com/OGeorgeDan/Manual_Testing_Jira/assets/149089987/f9e59f11-9dd6-4b4e-8037-f749e948d042)

![Test Metric 2](https://github.com/OGeorgeDan/Manual_Testing_Jira/assets/149089987/deffc80f-5595-415b-a4bb-f39ca6db939a)

![Test Metric 3](https://github.com/OGeorgeDan/Manual_Testing_Jira/assets/149089987/80c29ff2-e875-4196-95f7-47c8e60986d8)


### 1.3 Test Analysis <br>
The testing process will be executed based on the application requirements. The requirements analysis has been done in order to implement the early testing test principle and the results can be found here 

> inserati linkul catre documentul de review. Parte asta specificata intre paranteze o puneti doar daca aveti cerinte si daca ati facut review)  ???

The following test conditions were found:

![Tests](https://github.com/OGeorgeDan/Manual_Testing_Jira/assets/149089987/7780117e-1508-4d7e-8707-a419d7f5edd7) <br>

### 1.4 Test Design <br>
Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here:
[Jira - Test file.pdf](https://github.com/OGeorgeDan/Manual_Testing_Jira/files/15297439/Jira.-.Test.file.pdf)

### 1.5 Test Implementation <br>
The following elements are needed to be ready before the test execution phase begins:
+ Testing environment is up and running.
+ All testing data is obtained.
+ Access has been granted for users. <br>

### 1.6. Test Execution <br>
Test cases are executed on the created test Cycle summary: Emag.ro_V1.0

Bugs have been created based on the failed tests. The complete bug reports can be found here: 

![Issues - Bug](https://github.com/OGeorgeDan/Manual_Testing_Jira/assets/149089987/2ad39058-ba55-425b-9107-147b052a7e14)

The following is a summary of the bugs that have been found: **ODGT-19** is tested by **ODGT-20** which creates **ODGT-22** as a bug due to a font error. <br>
Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

### 1.7 Test Completion <br> 
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team.

The traceability matrix was generated and can be found here: 

![Traceability Matrix](https://github.com/OGeorgeDan/Manual_Testing_Jira/assets/149089987/aea54aa3-a78e-4a3e-bc20-caf060ef2bd1)

Test execution chart was generated and can be found below.

![Raport - Dashboards](https://github.com/OGeorgeDan/Manual_Testing_Jira/assets/149089987/f7fca136-568f-4f53-890d-3e27e7148500)

The final report shows that a number 2 tests have failed of a total of 10. <br>
A number of 1 total bugs were found, from which the priority is: 0 are high and 1 is medium. <br>

During the testing phase 8 stories were created which are under 2 epics. The 1st epic, has as a main goal, the login functionality on the website https://www.emag.ro/ and the submenus and respectively their actions under "Contul meu" section, and the 2nd epic is oriented towards the "Suport Clienti -> Contact" section, located in the footer, checking and testing the functionality of the buttons and that the pages are displayed correctly.
These 8 stories are followed by 10 test cases, which test different functionalities on the website. 
From these 8 stories only 6 of them are tested. 
From the 10 test cases, only 7 are executed. 
One single bug has been identified, with it being a minor bug with a low severity it does not affect the functionality of the platform in any way, it's just a font error in a subsection of the site, although the bug will be solved in the future. 

