# API---Django-Python  --  Two separate API's below.  

tutorial - This API uses Python with a Django framework.  It has built-in Administrator's authority to allow permission to change, add, delete users and/or groups of users.  You can choose to see the data in API or JSON format. The Administrator must have a valid username and password to validate authenticity.  It uses templating to make the site more appealing and easier to use.  The API also validates new information being entered by the Administrator, including username, email address (if entered) and other fields.  Object-relational mapping is used to create kind of a 'virtual environment' to use and run on your machine.

myproject - This API also uses Python with a Django framework.  Likewise, this API has built-in Administrator's authority to allow permission to change, add, delete users and/or groups of users and employees.  The Administrator must have a valid username and password to validate authenticity.  Templating is utilized to make viewing more appealing and easier to use.  The API also validates new information being entered by the Administrator, including username, email address (if entered) and other fields.  Object-relational mapping is used to create kind of a 'virtual environment' to use and run on your machine.
      Additional functionality - the administrator can do searches on users, groups or employees.  Since this one deals with an additional employee list, when setting up an employee the administrator declares Active status, Staff status, Super User status and can grant specific permission for this employee to see or enhance specific data.  The administator can also delete one or multiple employees at one time.  When the administrator is all done making whatever changes needed to be made, when returned to the main page, a summary log is displayed to show what has been effected.  Also, upon logging out a pleasant exit message is displayed.
