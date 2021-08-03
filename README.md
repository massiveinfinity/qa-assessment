# QA Assessment

In this asssessment, you will be required to install [Robot Framework](http://robotframework.org/) to perform the automation test.
You will be writing scripts to test functionalities, output or certain conditions based on this website https://opensource-demo.orangehrmlive.com/

## Objectives

1. To test familiarity with a test automation framework. 
2. To test adaptability to working with something new.

## User Requirements

1. Install Robot Framework and Selenium Web Driver on local machine. 
2. Install Chrome driver and use it for testing.
3. Perform test scenarios as documented below.

> Please note down the duration spent to complete the assessment. You should not take any longer than 6 hours to complete it.

At the end of your assessment, you should submit:
1. Source files of written test.
2. Generate and obtain report of automated test. Files obtained should include:
  - log.html
  - output.xml
  - report.html
  - Any screenshots if applicable

Please make sure the submitted source files would be executable for us to run the test successfully.

## Test Scenarios

### Test Case 1: Login Page - Authenticate Successfully

Registered user should be able to successfully login into the admin panel

#### Preconditions

You may use the account details below to login:

> Username: Admin 
>
> Password: admin123

#### Assumptions
A supported browser is being used.

#### Steps
1. Open a new page in the browser.
2. Navigate to https://opensource-demo.orangehrmlive.com/ 
3. Fill in the account details in the login screen.
4. Click on Login button.

#### Expected result

The *dashboard* screen should be displayed in the admin panel as the default view after
successful login.

<br /> 

### Test Case 2: Logout

Successfully login user should be able to logout from the admin panel.

#### Preconditions

User should already be logged into the admin panel.

#### Assumptions

A supported browser is being used.

#### Steps

1. From the admin panel, click on top right dropdown (Shows Welcome Admin ). 
2. Click on Logout option.

#### Expected result

Login page would be shown again to indicate a successful logout.
