
**AppData module for access control and data parse:**

**Brief:**
    
   AppData provides an full access control with visual request and hash validation
    for desktop API based on PyQt5.
    
+ **_load_user_data** private method allows the user to handle web service data, google
    sheets for this example, and creates a .json file from it if it doesn't exist.
######Note:
   To access a google spreadsheet from python and handle data from there follow the link below to
    _know-how_
    
   https://towardsdatascience.com/accessing-google-spreadsheet-data-using-python-90a5bc214fd2
    
+ **access_request** public method rise a dialog asking for user and password validation.
+ **user_register** public method for user registration with form graphic object, email 
format rule check, password requires check and empty fields check.

######Note: 
 User and password validation were tested under md5 hash format.
 Encrypting is a specific task of security. Don't use this example for commercial purposes or
 to handle sensitive data.
