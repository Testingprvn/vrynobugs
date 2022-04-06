## **Bugs List**
**Bugs Related to Email**
* Email is not coming add user action

**Bugs Related to functionality**

 _these will be picked up once notes are fixed_
 
* When someone tries to add a new user then in roles selection field, an "undifined" values is added extra other than the role selceted
* In permissions, users can't change the permission. Toggle button does not change it's state
* All the permissions for all roles is coming as "not allowed" by default even for instance owner and admin

### **Bugs In General**

#### Contacts

 * Add contact button shows "Accounts" instead contact
 * Contact dashboard starts with lower case rest modules are in camel case.
 
 #### Organizations
 
 * if user adds a call log from organizations page and selects multiple related items including contact, deal, and lead. that call log does not show under those lead, deal or contact
 
 #### Activities
 
* Reminder date can not be greater than the due date in meeting and task.
* Meeting end date can not be less than the start date of meeting.
* In related to field by default "account" module is selected in module list but if user try to search any recod name in that then he/she can not do that action until or unless user switches module twice from the module list.
 
 #### Deals
 
* If user selects deal module along with all other modules while creating a meeting, the created meeting does not show under respective deal but it is visible in all other module records

### Bugs Found on 01/04/2022

 * In Recycle bin, "deleted by" field shows id instead of value in it.
 * UI of "attach" button in attachments needs to be corrected
 * Clicking on a URL record added using attachments, redirects user to an empty page.
 * User can upload any type of file in attachments. this needs to be corrected
 
**Issues with Notes**

 * If a user selects a file to attach to the notes section, after cliking the save button attach file section does not clear the previous data.
 * As of now user can attach any file type in notes be it CSV or .py of any other, need to fix this.
 * UI of cancel button on attachments in notes needs to be updated. it is too tiny to click on.
 * If user try to upload more than one file in notes section then it shows an error "NoneType' object is not subscriptable"
 * If user clicks on "edit note" icon continuously on multiple notes( all of those should have attachments other than image file) then the edit page shows all the attachments in single note.
