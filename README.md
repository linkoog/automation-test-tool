# Automation-Test-Tool

Automation Test Tool for RESTful API


Author	:  Yu Dong Wang (Dom Wang)

Version	:  1.0

Date	:  Feb 8, 2017

Email	:  wangyudongwyd@126.com

---------------------------------------------------------------------------------------------------------------------
Operation steps:

You should first make a directory with name 'autotest'.

Copy file 'autotest-1.0.jar' and 'conf.zip' to 'autotest'

Unzip 'conf.zip' to 'autotest'

*Note*: You must put 'autotest-1.0.jar' and 'conf' in the same directory.

You should write your test cases in directory 'conf' with reference to the demo and the document ‘AutomationTest.doc’.

After that, run this runnable JAR 'autotest-1.0.jar', double click it to run the cases.

Directory tree:

autotest
├── autotest-1.0.jar
└── conf
    ├── assertions
    │   ├── assert_case_http_get.json
    │   ├── assert_case_http_post.json
    │   └── assert_case_http_put.json
    ├── AT_Tasks.json
    ├── body
    │   ├── body_case_http_post.json
    │   └── body_case_http_put.json
    └── cases
        ├── case_http_delete.json
        ├── case_http_get.json
        ├── case_http_post.json
        └── case_http_put.json

You can see the document ‘AutomationTest.doc’ to know more about the automation test tool.  

