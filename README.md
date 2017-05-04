# About the Automation Test Tool

Automation Test Tool for RESTful API


Author	:  Yu Dong Wang (Dom Wang)

Version	:  1.1

Date	:  May 3, 2017

Email	:  wangyudongwyd@126.com

---------------------------------------------------------------------------------------------------------------------

![image](https://raw.githubusercontent.com/wangyudongdom/Automation-Test-Tool/master/screenshot_3.png)

---------------------------------------------------------------------------------------------------------------------
# Here list the steps of the demo

1. Unzip 'autotest-1.1.zip';


2. Stop tomcat service; 

3. Copy 'RestServer-1.0.war' to tomcat directory 'webapps/';

4. Start tomcat service;

5. Update these files to your real port number and real host in directory 'work/cases/', related files:
case_user_add.json, 
case_user_delete.json, 
case_user_get.json, 
case_user_update.json.

5. Double click this runnable JAR 'autotest-1.1.jar', and click button 'run'.

---------------------------------------------------------------------------------------------------------------------
# The usages of this tool

1. Unzip 'autotest-1.1.zip' you can get 'autotest-1.1.jar' and the directory 'work'.

   *Note*: You must put 'autotest-1.1.jar' and 'work' together in one directory.

2. You should write your test cases in directory 'work' with reference to the demo and the document ‘AutomationTest.doc’.

3. After that, run this runnable JAR 'autotest-1.1.jar', double click it to run the cases.
   You can see the document ‘AutomationTest.doc’ to know more about the automation test tool.
   
   Directory tree: 

   ![image](https://raw.githubusercontent.com/wangyudongdom/Automation-Test-Tool/master/screenshot_4.png)


