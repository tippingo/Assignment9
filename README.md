# Assignment9
Description:
This microservice provides login functionality. You use application.txt to communicate with the microservice, and login.txt will be used to store the user login information.

Example Commands:
 - Authenticate New Username Password Permissions (Adds new login)
 - Authenticate Login Username Password (Checks user credentials)
 - Authenticate Reset Username Password Permissions (Changes existing user information)
 - Authenticate Delete Username (Deletes specified user)

Possible Return Values:
 - Authenticate Failed (The request failed IE: username and password are incorrect)
 - Authenticate Complete (The request was successful IE: user was deleted from system)
 - Authenticate Complete Permissions (The login was succesfull)

