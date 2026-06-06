## Basic 2 
Level 2
Network Security Sam set up a password protection script. He made it load the real password from an unencrypted text file and compare it to the password the user enters. However, he neglected to upload the password file...

## Solution
In this challenge, we are told that Sam forgot to upload his password file. Therefore, the program won't be comparing the user's password, and we can just leave the password empty, and click submit. The application will compare the empty string to the string on the server (that also empty), and because " " == " ", we will pass the authectication form.
