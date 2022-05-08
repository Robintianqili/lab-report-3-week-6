# Lab report 3

## 1. the ssh configuration

* firstly, find the .ssh file in the desktop

![image](6.PNG)

* create or find the file "config", and then write lines below:

`Host ieng6`

`HostName ieng6.ucsd.edu`

`User cs15lsp22zzz(replace zzz with someone's own username)`

*in this case, the alias is ieng6, HostName and User will indicate the remote server of the .ssh*

![image](7.PNG)

* in the terminal page, we can simply input ssh (Host) to log in the remote server. Then, we could use scp to upload the files.

![image](8.PNG)  

## 2. Set up Github Access
* the new ssh key in Github website

![image](5.PNG)

* the private ssh key in my own computer

![image](6.PNG)

* running git commands to commit and change to github while log into the ieng6 server

![image](10.PNG)

## 3. copy whole directory by using scp recursively

*  copying your whole markdown-parse directory to your ieng6 account.

![image](99.png)

*  logging into your ieng6 account after doing this and compiling and running the tests for your repository.

![image](100.PNG)

* combining scp, ;, and ssh to copy the whole directory and run the tests in one line.

![image](11.PNG)
