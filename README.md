# Automation-Test-Tool

Automation Test Tool for RESTful API


Author	:  Yu Dong Wang (Dom Wang)

Version	:  1.1

Date	:  May 3, 2017

Email	:  wangyudongwyd@126.com

---------------------------------------------------------------------------------------------------------------------
Here list the steps of the demo:

1. Unzip 'autotest-1.1.zip';


2. Stop tomcat service; 

3. Copy 'RestServer-1.0.war' to tomcat directory 'webapps/';

4. Start tomcat service;

5. If your port number of tomcat is not 8080, please change to the real port number in directory 'work/cases/', related files:
case_user_add.json
case_user_delete.json
case_user_get.json
case_user_update.json

5. Double click this runnable JAR 'autotest-1.1.jar', and click button 'run'.

---------------------------------------------------------------------------------------------------------------------
The usages of Automation Test Tool:

1. Unzip 'autotest-1.1.zip' you can get 'autotest-1.1.jar' and the directory 'work'.

   *Note*: You must keep 'autotest-1.1.jar' and 'work' together in one directory.

2. You should write your test cases in directory 'work' with reference to the demo and the document ‘AutomationTest.doc’.

3. After that, run this runnable JAR 'autotest-1.1.jar', double click it to run the cases.
   You can see the document ‘AutomationTest.doc’ to know more about the automation test tool.
   
   Directory tree: 

![image](https://raw.githubusercontent.com/wangyudongdom/Automation-Test-Tool/master/screenshot_4.png)

    Test report：
![image](https://raw.githubusercontent.com/wangyudongdom/Automation-Test-Tool/master/screenshot_3.png)
