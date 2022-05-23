# Responsive-Fight
Responsive is an application that renders plain HTML and Javascript.
The cypress regression test cases are included to cover the following scenarios:
1. RegressionUserCreation Suite contains test cases to :
        Verify if the user creation is successsful.
        Verify if the user is created when password and retype password fields are not matching.
        erify if the user is created ewhen the user name is already existing.
2. RegressionUI Suite contains test cases to :
        Login with correct username password
        Login with blank/empty password
        Login with invalid username password combination
        Verify the UI in login page
3. RegressionChallenges suite contains test cases to:
        Verify the different challanges - but this has been removed from the application
4. RegressionAllBattlesCorrect suite contains test cases to:
        Complete the challenges successfully and navigate to the leaderboard.
5. RegressionAllBattlesWrong suite contains test cases to:
        Exit teh challange by choosing a wronhg answer choice.
        
        
To Run the test:
Download this repo and run the below scripts:

1. Generate package.json file using: npm init
2. Install cypress : npm install cypress --save-dev 
3. Open the cypress test runner  : node_modules/.bin/cypress open
and choose the test suite to be run by clicking on the test suite
or 
run all the tests in the cypress test directly in headed mode : ./node_modules/.bin/cypress run --headed
  
