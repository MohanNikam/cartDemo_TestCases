# cartDemo_TestCases
Test cases are related to Ecommerce website _cart demo

Hi,
Below mentioend steps details will helpful to run the robot framework code on your machine.

Robot framework using python and Pycharm IDE
1. Install Pycharm Community edition (IDE) from the website
2. Install Python compatible version Python 12
3. Set the environment variable and path 
4. Once installation done then Go to File->Settings-> Project Python-> Python interpreter
5. Click on + icon to add packages which are required to run the robot files code
6. Add below mentioned packages
	1. robotframework
	2. selenium
	3. robotframework-seleniumlibrary
	4. robotframework-DataDriver
Once these packages are install successfully
7. Here we need to add plugin for the framework
	1. intellibot @seleniumLibrary Patched
	2. Hyper RobotFramework Support (if required)
8. Here we go to run the Robotframework code

For the mentioend Cart demo project
I have used the keyword and data driven framework for the automation test execution
also 
I have created the Smoke suite which will run the complete  positive flow in one go.
 for  this you need to run the command
	-> robot TestCode/AutomatioDemo/Smoke_cartDemo.robot
	
Anothe code i have created for the login test cases to validate the invalid login test scenarios.
for this you need to run the command
	-> robot TestCode/AutomatioDemo/Loginexcel.robot


also refer the requirements.txt to understand the required packages details 
	-> pip freeze > requiremets.txt 
	
	above mentioned command creates a list of all the installed packages in the 
	virtual environment, along with their versions. This list can be used later to 
	recreate the same virtual environment on another machine



Thanks and reagrds
Mohan Nikam
Email: mohannikam0934@gmail.com
If any query please mail me.

