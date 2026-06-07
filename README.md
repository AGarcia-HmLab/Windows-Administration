# Windows Admininstation - Lab01
## Description
Learn entry level IT administration
## Objectives
- Create a Local Windows user account
## Skills Learned
-Account creation
-Password resets
## Steps
1. Log into Windows VM on VirtualBox
2. On desktop, open Command Prompt found by searching " cmd " and running it as an admin.
3. In command prompt, verify current user by entering "whoami" then enter "netuser" to display current account on pc
4. Create a new user by entering "net user Bob Password123! /add". This crates a new user by using the command "net user" followed by the users name and temporary password. The "/add" creates the account.
5. The account can then be verified it was created by entering "net user" again and seeing Bob in local users
<img width="1920" height="1080" alt="Screenshot (20)" src="https://github.com/user-attachments/assets/1e6eeede-b54a-47a0-93c0-b05655f4e025" />  Account details can be verified by entering "net user Bob"
6. Changed Bobs pasowrd by entering "net user Bob NewPassword123!"
<img width="1920" height="1080" alt="Screenshot (21)" src="https://github.com/user-attachments/assets/52186d2c-584c-4cac-996f-49c4fdd5caf5" />
