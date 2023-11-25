### LAB2

### 1. Create a user account with the following attribute
 username: islam
 Fullname/comment: Islam Askar
 Password: islam
![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/ea85080e-ed4a-449f-ade8-83f023f1f179)


### 2. Create a user account with the following attribute
 Username: baduser
 Full name/comment: Bad User
 Password: baduser
![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/81fc1ae4-0e19-4885-858b-1d1356c52f8b)

### 3. Create a supplementary (Secondary) group called pgroup with group ID of 30000
### 4. Create a supplementary group called badgroup

Ans of 3,4:

![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/cf1243ba-7758-47e3-9eac-e128a87bc831)

### 5. Add islam user to the pgroup group as a supplementary group
### 6. Modify the password of islam's account to password

Ans of 5,6:

![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/bd9a9a5c-6736-4a9c-82bd-6ae53ef5b110)

### 7. Modify islam's account so the password expires after 30 days
![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/8c7f553b-2a5d-4e24-92bb-359c1bb93c6c)

### 8. Lock bad user account so he can't log in
![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/f48a3314-ac57-4f0b-b85b-586a7aa01c40)

### 9. Delete bad user account
![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/b4a06653-78ac-4f08-9982-18f36fccd335)

### 10. Delete the supplementary group called badgroup.
![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/4b5dd464-0080-4b0b-9fad-7aed278e2689)

### 13. Create a folder called myteam in your home directory and change its permissions to read only for the owner.
### 15. Try to access (by cd command) the folder (myteam)

Ans of 13,15:

![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/416361d6-a427-481a-bdb3-6207c2cf86d4)

### 14. Log out and log in by another user
![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/5a6ad881-2a98-4630-9fa7-435f5a661331)

### 16. Using the command Line
###  Change the permissions of oldpasswd file to give owner read and write permissions and for group write and execute and execute only for the others (using chmod in 2 different ways)
![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/029b67b5-bfc2-4654-98d9-3d164664c777)

###  Change your default permissions to be as above.
![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/975e7290-e4fb-41f2-a682-fab5d8bb32d6)

###  What is the maximum permission a file can have, by default when it is just created? And what is that for directory.

Ans:

permission a file can have: 666
 
permission a dir can have: 777

###  Change your default permissions to be no permission to everyone then create a directory and a file to verify.
![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/836787e1-f60c-4bf7-a9d8-ab839bcaa3cf)


### 17. What are the minimum permission needed for:
###  Copy a directory (permission for source directory and permissions for target parent directory)
Ans:

permission a src dir can have to copy: --x

permission a dist dir can have to copy: -wx

###  Copy a file (permission for source file and and permission for target parent directory)
Ans:

permission a file can have to copy: r--

permission a dist dir can have to copy: -wx
       
###  Delete a file
Ans:

permission for a file: ---

permission for a dir: -wx

###  Change to a directory
Ans:

permission to change a dir: --x

###  List a directory content (ls command)
Ans:

permission to list a dir content: r-x

###  View a file content (more/cat command)
Ans:

permission to view a file content: r--
    
###  Modify a file content
Ans:

permission to modify a file content: -w-

### 18. Create a file with permission 444. Try to edit in it and to remove it? Note what happened.
![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/78d79f94-089f-4e06-9ee3-c2e9c0fa83a8)


### 19. What is the difference between the “x” permission for a file and for a directory?

Ans:

x for file: give the right to run this file. (but files don't take x permission by default)

x for dir: give the right to enter this dir by (cd). (dir can take x permission by default)
