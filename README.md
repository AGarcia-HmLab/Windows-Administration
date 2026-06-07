# Windows Admininstation - Lab01
## Description
Here I Learned entry level IT administration tasks using command prompt on a Windows 11 Home Pro VM in VirtualBox. 
## Objectives
- Learn daily entry level IT tasks
## Skills Learned
- Account creation
- Password resets
- Disabling and enabling accounts
- Commands:
  - net user
  - net user Bob Password123! /add
  - net user Bob
  - net user Bob NewPassword123!
  - net user Bob /active:no
  - net user Bob /active:yes 
## Steps
1. Log into Windows VM on VirtualBox
2. On desktop, open Command Prompt found by searching " cmd " and running it as an admin.
3. In command prompt, verify current user by entering "whoami" then enter "netuser" to display current account on pc
4. Create a new user by entering "net user Bob Password123! /add". This crates a new user by using the command "net user" followed by the users name and temporary password. The "/add" creates the account.
5. The account can then be verified it was created by entering "net user" again and seeing Bob in local users
<img width="1920" height="1080" alt="Screenshot (20)" src="https://github.com/user-attachments/assets/1e6eeede-b54a-47a0-93c0-b05655f4e025" />Account details can be verified by entering "net user Bob"
6. Changed Bobs pasowrd by entering "net user Bob NewPassword123!"
<img width="1920" height="1080" alt="Screenshot (21)" src="https://github.com/user-attachments/assets/52186d2c-584c-4cac-996f-49c4fdd5caf5" />
7. Disable user account with command "net user Bob /active:no" and verify by commanding "net user Bob" again which should display account not active. I Learned the security concept of disable then delete later in case data is needed from account
<img width="1920" height="1080" alt="Screenshot (22)" src="https://github.com/user-attachments/assets/160c709a-0e0d-49c3-a958-f45690741da3" />
8. Enabled Bobs account again with command "net user Bob /active: yes". Can be verified again with command "net user Bob"
<img width="1920" height="1080" alt="Screenshot (23)" src="https://github.com/user-attachments/assets/597e52b4-ebb1-4fe2-a5c6-702e70b102ac" />\

## comments/notes
Much simpler of a processs than I thought. 
