# BDD
BDD automation framework

Instructions : Just import the JAR file given and run the TestRunner.java file as JUNIT application

Dependencies : To capture captcha output tesseract Jars needs to be added and Uncomment the code for Captcha reading

Highlights : 

Added another "when" step in Feature file . As there should be test case from navigating home page to contact us page. Because if this link is broken then it will be Critical severity 

Made the framework more scalable by Using Test data as Examples in Feature file. Now we can add different test values for each field for further validations of text boxes present in Contact Us page

Used Page Object Model for BDD framework 

Bug Identified : "Company" Field in Contact Us page was not mentiones as "Required". But clicking on Send Button is giving Validation error on  "Company" Field saying "Mandatory Field"

Improvements :

Could have added the screeshot for the failure through selenium. But due to time constraint just giving the failure on high level.

