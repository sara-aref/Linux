lab1

### 2. What is the difference between cat and more command?
cat: display the contents of the file but the output will scroll off the screen.     
more: display the contents of the file but it display the output one screenful at a time.

### 3. What is the difference between rm and rmdir using man?
rm: remove file or directories that not empty(rm -r).
rmdir: remove empty directories.  

### 4. Create the following hierarchy under your home directory:
![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/46cb5396-7d88-46cf-81a7-437d791684b7)


### a. Remove dir11 in one-step. What did you notice? And how did you overcome that?
Ans: dir11 isn't removed because there is file1 in this dir11, so we use rm -r
![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/fd067ca8-1853-499d-83c1-fd77b607d9a5)


### b. Then remove dir12 using rmdir –p command. State what happened to the
Ans: dir1 is removed with dir12
![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/0ebd0b6d-ac36-4d7a-a63b-f7e5f228971c)

### c. The output of the command pwd was /home/user. Write the absolute and relative path for the file mycv
1- absolute path: /home/sara/docs/mycv
2- relative path: docs/mycv

### 5. Copy the /etc/passwd file to your home directory making its name is mypasswd.
### 6. Rename this new file to be oldpasswd.
Ans of 5,6:
![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/8232087c-7cca-4a96-befb-8b18b0629e86)

### 7. You are in /usr/bin, list four ways to go to your home directory
1- cd

2- cd ~

3- cd $HOME

4- cd /home/sara

### 8. List Linux commands in /usr/bin that start with letter w
![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/d5a9d45c-36d2-4e6b-ab6f-0d3ff42f2b4f)
   
### 9. Display the first 4 lines of /etc/passwd
### 10.Display the last 7 lines of /etc/passwd
Ans of 9,10:
![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/a228f3e9-7fd0-438d-825f-d49748a772e7)

### 11.Display the man pages of passwd the command and the file sequentially in one command.
Ans: man -a passwd

### 12.Display the man page of the passwd file.
Ans: man passwd

### 13.Display a list of all the commands that contain the keyword passwd in their man page.
![UNFOUND](https://github.com/sara-aref/Linux/assets/147546807/8d217eb6-6d9f-4e4a-8be1-4c52078f0718)
