# Double Submit Cookies Pattern
This project demonstrates how to use CSRF Tokens and Session IDs to validate sessions and users using PHP.

Setup Requirements:
WAMP (for windows users) or LAMP (for Linux users) installed on your machines.

Running the App:
Clone this repository Use master branch!

Steps:

Copy all the files in the directory. 
Paste the files in to a directory in the path /var/www/html (for LAMP users) 
Open a web browser and navigate to http://localhost/[directoryname]/index.php


User:
username akila and password akila123 to log in.

Description:
Upon successful user login, the server generates a Session ID and a CSRF Token for the session. Session ID and CSRF token is set as browser cookies. When user submits the form, The server validates whether the Session ID and CSRF Token matches. When user logs out Session ID and CSRF Token are deleted from the server making them unusable.

Note:

Auto generated UUIDs are used for Session ID and CSRF Token.

Blog:
https://medium.com/@akiller_68392/double-submit-cookies-pattern-7a9e513e8dfc
