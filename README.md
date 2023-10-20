# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

### Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

#### Syntax: ls

![ex1_01](https://github.com/BALUREDDYVELAYUDHAMGOWTHAM/Ex-01-Linux-Commands/assets/119559905/d7b12628-dc2e-4b5a-81b5-e997b9c43e0b)

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

#### Syntax: pwd

 ![ex01_02](https://github.com/BALUREDDYVELAYUDHAMGOWTHAM/Ex-01-Linux-Commands/assets/119559905/27bf2a96-201c-4f82-a083-12a972947a21)

### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

#### Syntax: mkdir <directory name>


![ex01_03](https://github.com/BALUREDDYVELAYUDHAMGOWTHAM/Ex-01-Linux-Commands/assets/119559905/0f1aa300-fc47-4f01-8a16-87cba0d0a408)

### 4)	rmdir Command

The rmdir command is used to delete a directory.

#### Syntax: rmdir <directory name>


![ex01_04](https://github.com/BALUREDDYVELAYUDHAMGOWTHAM/Ex-01-Linux-Commands/assets/119559905/30c628af-607b-46b5-8b50-8c6e3e881930)



### 5)	cd Command

The cd command is used to change the current directory.

#### Syntax: cd <directory name>


![ex01_05](https://github.com/BALUREDDYVELAYUDHAMGOWTHAM/Ex-01-Linux-Commands/assets/119559905/8f18b22b-17c6-44f6-9ed2-e2d94007c468)



### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

#### Syntax: cat [OPTION]... [FILE]..

 ![ex01_06](https://github.com/BALUREDDYVELAYUDHAMGOWTHAM/Ex-01-Linux-Commands/assets/119559905/537eb527-3480-47c7-8757-e6bf751983a6)

### 7)	cp Command

The cp command is used to copy a file or directory.

#### Syntax: cp <existing file name> <new file name>

![ex01_07](https://github.com/BALUREDDYVELAYUDHAMGOWTHAM/Ex-01-Linux-Commands/assets/119559905/99c322b2-21e2-45cb-9db2-a6d27bd30a30)


### 8)	gedit Command
The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.
#### Syntax: gedit file_name

![ex01_08](https://github.com/BALUREDDYVELAYUDHAMGOWTHAM/Ex-01-Linux-Commands/assets/119559905/e12558fc-db2c-40a7-bf63-5fb33c13b0ef)

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

#### Syntax: su <user name>

![ex01_09](https://github.com/BALUREDDYVELAYUDHAMGOWTHAM/Ex-01-Linux-Commands/assets/119559905/6598e64a-8ef2-4319-9e45-94c5b568d0bd)

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

#### Syntax: mv <file name> <directory path>

 ![ex01_10](https://github.com/BALUREDDYVELAYUDHAMGOWTHAM/Ex-01-Linux-Commands/assets/119559905/41017bc8-3643-4487-bbf0-66fb495729c2)

### 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

#### Syntax: rename 's/old-name/new-name/' files

![ex01_11](https://github.com/BALUREDDYVELAYUDHAMGOWTHAM/Ex-01-Linux-Commands/assets/119559905/37c1c9b2-eec0-49ac-b590-4b7a8d6355cf)

### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

#### Syntax: head <file name>

![ex01_12](https://github.com/BALUREDDYVELAYUDHAMGOWTHAM/Ex-01-Linux-Commands/assets/119559905/bd10a0ac-f562-4980-b993-15691b63980b)

### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

#### Syntax: tail <file name>

 ![ex01_13](https://github.com/BALUREDDYVELAYUDHAMGOWTHAM/Ex-01-Linux-Commands/assets/119559905/d429d43e-37df-4a1f-aafc-143f642a662f)

### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

#### Syntax: id

![ex01_14](https://github.com/BALUREDDYVELAYUDHAMGOWTHAM/Ex-01-Linux-Commands/assets/119559905/03a26534-fb74-4de2-a07c-4fbafd502ce5)

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

#### Syntax: command | grep <search word>

![ex01_15](https://github.com/BALUREDDYVELAYUDHAMGOWTHAM/Ex-01-Linux-Commands/assets/119559905/6e6d7a7e-b791-43c6-b574-bc2b4311e08d)

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

#### Syntax: command | tr <'old'> <'new'>

![ex01_16](https://github.com/BALUREDDYVELAYUDHAMGOWTHAM/Ex-01-Linux-Commands/assets/119559905/3495925b-9e2f-4d67-b5b9-fe7460aea5f1)

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

#### Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

#### Syntax: tar[options][archieve-file] [file to be archieved]
#### $ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

#### Syntax: chown owner_name file_name

![ex01_19](https://github.com/BALUREDDYVELAYUDHAMGOWTHAM/Ex-01-Linux-Commands/assets/119559905/626082f1-911f-4908-bc10-dfc6030de544)

### 20)	make Command

The make command is used for building and maintaining group of program.

#### Syntax: make [-f makefile][options]…….[targets]….

![ex01_20](https://github.com/BALUREDDYVELAYUDHAMGOWTHAM/Ex-01-Linux-Commands/assets/119559905/7d2b1662-d4ab-4a6f-a8cc-54df3d00480c)

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

#### Syntax: ifconfig[options][interface]

![ex01_21](https://github.com/BALUREDDYVELAYUDHAMGOWTHAM/Ex-01-Linux-Commands/assets/119559905/79a5f41b-8385-4822-a437-1859a85b2e54)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

#### Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

#### Syntax: host <domain name> or <ip address>

![ex01_23](https://github.com/BALUREDDYVELAYUDHAMGOWTHAM/Ex-01-Linux-Commands/assets/119559905/f0125357-ed37-47ad-881e-2590965eebe8)

### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

#### Syntax: gzip <file1> <file2> <file3>..


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

#### Syntax:sort <file name>

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

#### Syntax: cal


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

#### Syntax: clear


### 28)	mail Command

The mail command is used to send emails from the command line.

#### Syntax: mail -s "Subject" <recipient address>

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

#### Syntax: df

### 30)	find Command

The find command is used to find a particular file within a directory.

#### Syntax: find.-name”*.pdf”





















### Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
