# demoUI
Demo-UI-Automation Framework

This framework is for UI Automation using selenium webDriver
- Build Tool: Maven
- Test Tool : TestNG
- Automation Tool: Selenium WebDriver (v3)
- Reporting: Default TestNG Reports
- VCS: Git
- WebDriver: Using WebDriver Manager
- PageObjects: Using PageFactory Model

Framework has different components
- Base Package
- Util Package
- PageObjects Package
- Test Package
- Pom.xml
- testNG.xml

Can execute multiple classes in parallel 
and every class has its own driver instance
Parallel classes execution sample has been provided in the project

Also, Project has multiple cross-browsers capability as well, this will require few changes in the xml files 
and totally based upon the requirements to requirements. 

To Start with project
Pre-requisites:
Java, maven,git and chrome/firefox browsers should be installed

Just run Command 
mvn clean install -U -DSuiteXmlFile=testng.xml

This command will gather all the necessary maven repositories at your local and run browsers in parallel executions.

Author: Aakash Gupta 

Any Suggestion/feedback or PR is highly appreciable.

Thanks 
