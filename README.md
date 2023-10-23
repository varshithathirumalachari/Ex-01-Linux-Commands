# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/f5ecc037-32a1-4661-b68f-e6dad96467b9)

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/41d9d4ab-386c-4a8c-8229-4e3aa47f1c18)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/52277ef1-f054-4575-af62-442be823cd04)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/b9d7538c-75a3-4834-90b7-44af532ef10b)

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/e36a7797-e3cd-40ed-a66b-4606e85d0134)

### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/635b9e1b-48ef-4a7e-8262-992986746b75)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/9c1b130d-31cf-409b-bbfd-0c48a1935587)


### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/834be56e-7185-4116-9c56-50211d7e5aa1)

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/e9e660d5-a79e-45f0-83b5-477556666ce6)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

 ![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/4b7e7cf8-2719-454e-ae1d-a57afebb2241)

## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/5d5678ae-7852-4be5-9287-0cffcfb711cf)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/c17881a9-d4d4-42bb-801e-5c3bf8f8ce12)

### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/eb6a3211-9c4f-4760-99c5-3638be15e150)
 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/31cd97e8-01d9-4d70-9573-bd3a8a8a8889)

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/572d0a55-5a4f-445f-ba0c-b298880d35a2)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/9530d7ec-2ffd-4de4-b492-8dcf1bdb70cc)

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/ef640790-eb9f-4751-9c61-faab3f664b57)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/d8819754-2a84-4b36-89e9-cf046dba50a8)

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/6b1a6794-78e3-43d3-8d18-da4c2edfea68)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name

$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/1143a749-1cb8-4801-b9c8-442834c01f4c)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/5580c2ac-c618-4a7a-9435-d76bf4d6dddf)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/51297707-82dd-416e-b3eb-3f4f1b83336d)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/e78526b5-fb47-43c8-8e70-96b80f13840a)

### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/036440e5-00a6-46f3-8ee4-8ff8960a1504)

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/49df4e61-4c9d-42c2-9a14-969a2a668004)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![image](https://github.com/varshithathirumalachari/Ex-01-Linux-Commands/assets/131793193/3c8dfcec-f414-4fdd-b5d7-e9fddf3e6845)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
