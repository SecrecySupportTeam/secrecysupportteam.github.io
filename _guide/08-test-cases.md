---  
title: Test cases
layout: guide
date: 2015-03-21
---  
# Why test cases?  
  
Secrecy is honestly quite a massive project, where users' files are at risk if version upgrades are not handled correctly, or if the UI is broken and users cannot access their files as they wish. We would like to keep a documented test case database so that we (and any other interested party) can test the product thoroughly before we push the release to production. 
 
Test cases should be written in a consistent flow (i.e. step 2 can be conducted immediately after step 1.), where an ACTION and a RESPONSE should be listed. 
 
Key: 
 
**ACTION** 
 
EXPECTED RESPONSE 
 
At any time, a quality assurance personnel can check the app's integrity by following the test cases from start to end. This way a consistency in different versions can be ensured. 
 
Note that this list is never complete. Please expand by adding new test cases. 
 
## Vault creation and handling 
 
**Create new vault "test" with password and confirm password as "test"** 
 
New vault called "test" should get created 
 
**When creating new vault, click on cancel** 
 
New vault should NOT get created 
 
**Wrong password combination** 
 
Alert the user and restrict vault creation 
 
**Try creating a vault with name that already exists** 
 
Alert the user and restrict vault creation 
 
**Try creating a vault with blank name and password** 
 
Alert the user and restrict vault creation 
 
**Try creating a vault with name but BLANK password** 
 
Alert the user and restrict vault creation 
 
**Click on the newly created vault** 
 
Prompt the user for password 
 
**Click on the newly created vault and enter WRONG password** 
 
Alert the user and restrict vault opening 
 
**Click on the newly created vault, do NOT enter password and hit ok** 
 
Alert the user and restrict vault opening 
 
**Click on the newly created vault and hit the X button** 
 
Restrict vault opening 
 
**Click on the newly created vault and enter CORRECT password** 
 
Open the vault 
 
## File Adding and Handling 
 
**Add few files (Photos)** 
 
The files should get added 
 
## User Settings 
 
## Upgrades 
