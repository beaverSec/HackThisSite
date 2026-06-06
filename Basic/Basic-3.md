# Basic 3

## Problem Overview
This time Network Security Sam remembered to upload the password file, but there were deeper problems than that.

## Solution
In this challenge, the aplication now use a form to validate the password (just like the previous challenge, but this one is for real). So the steps we gotta do are:

### 1. Check the source code, espcially at the `<form>` part 

<img width="976" height="259" alt="image" src="https://github.com/user-attachments/assets/1fad43a5-8791-4381-9694-6483d6090618" />

At the picture above, we know that there is a exposed path file, and we can try to access it by adding password.php at the end of the URL (https://www.hackthissite.org/missions/basic/3/ to https://www.hackthissite.org/missions/basic/3/password.php).

### 2. The password is found! `7710c5d9`
<img width="867" height="273" alt="image" src="https://github.com/user-attachments/assets/eb4de865-6093-4fa5-917d-3611c6a61531" />
