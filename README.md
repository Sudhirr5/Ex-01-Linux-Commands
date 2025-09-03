# Ex-01-Linux-Commands
### Name : SUDHIR KUMAR. R
### Reg No. : 212223230221

## Aim:
To study the execution of various Linux operating system commands.

## Linux:
Linux is an open-source operating system. The kernel is the heart of Linux OS whichhelps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.
Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.

## Commands:

### 1)	ls Command
The ls command is used to display a list of content of a directory.
 Syntax: ls

<img width="615" height="68" alt="Screenshot 2025-08-29 094121" src="https://github.com/user-attachments/assets/7e150066-e372-4ecf-aaf7-deb0995675dc" />
 
### 2)	pwd Command

The pwd command is used to display the location of the current working directory.
Syntax: pwd

<img width="339" height="111" alt="Screenshot 2025-08-29 094151" src="https://github.com/user-attachments/assets/48bb9d4d-5de9-443c-a0b6-7022926c2f05" />

### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.
Syntax: mkdir <directory name>

<img width="372" height="103" alt="Screenshot 2025-08-29 094300" src="https://github.com/user-attachments/assets/16f5f207-6036-41ea-ae63-5dc767d92932" />

### 4)	rmdir Command

The rmdir command is used to delete a directory.
Syntax: rmdir <directory name>

<img width="351" height="96" alt="Screenshot 2025-08-29 094355" src="https://github.com/user-attachments/assets/e7ab7694-fef7-4998-bd06-be16e3ae6557" />

### 5)	cd Command

The cd command is used to change the current directory.
Syntax: cd <directory name>

<img width="447" height="87" alt="Screenshot 2025-08-29 094458" src="https://github.com/user-attachments/assets/df569f95-3ec8-43cc-abe7-f164a3029760" />

### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.
Syntax: cat [OPTION]... [FILE]..

<img width="489" height="314" alt="Screenshot 2025-08-29 094842" src="https://github.com/user-attachments/assets/af85027f-1337-4d6e-a256-295c96b166ba" />

### 7)	cp Command

The cp command is used to copy a file or directory.
Syntax: cp <existing file name> <new file name>

<img width="375" height="217" alt="image" src="https://github.com/user-attachments/assets/16db94bd-76df-4e10-b39b-61feb58c47d7" />

### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.
Syntax: gedit file_name
<img width="311" height="40" alt="image" src="https://github.com/user-attachments/assets/e0cd0d2d-c53c-4d0e-9952-5ecb36948da6" />

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.
Syntax: su <user name>

<img width="301" height="95" alt="image" src="https://github.com/user-attachments/assets/3cd18409-360e-44b1-aa4d-2a9a20ea4a49" />

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.
Syntax: mv <file name> <directory path>
<img width="291" height="48" alt="image" src="https://github.com/user-attachments/assets/2378c8b0-31e4-4bd3-bad9-55961fd70e27" />
<img width="312" height="70" alt="image" src="https://github.com/user-attachments/assets/ae23a1fa-d054-4068-91d7-25669812cb6b" />

## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.
Syntax: rename 's/old-name/new-name/' files
<img width="303" height="83" alt="image" src="https://github.com/user-attachments/assets/858ed076-4a0c-497b-a10a-c6fe456d789a" />

### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.
Syntax: head <file name>
<img width="387" height="450" alt="image" src="https://github.com/user-attachments/assets/34f4f3c1-6fbf-4b1e-8a85-8b84667b6fc9" />

### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.
Syntax: tail <file name>

<img width="342" height="253" alt="image" src="https://github.com/user-attachments/assets/31039137-70a5-4d5c-9ba8-3ca078210c07" />

### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).
Syntax: id
<img width="645" height="96" alt="image" src="https://github.com/user-attachments/assets/3b69b38f-286e-4cd1-b75d-2605ca99d54d" />

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.
Syntax: command | grep <search word>
<img width="322" height="242" alt="image" src="https://github.com/user-attachments/assets/acf9d48a-0682-4290-ad85-c32f4f5bd732" />

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.
Syntax: command | tr <'old'> <'new'>
<img width="317" height="237" alt="image" src="https://github.com/user-attachments/assets/c8f6c5af-97d0-4993-afe6-9f3099eb05b6" />

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)
Syntax: chmod<options><permissions><file_name>
<img width="482" height="156" alt="image" src="https://github.com/user-attachments/assets/0972298a-ca0b-4e99-a91c-3cdf005336ae" />

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.
Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

<img width="391" height="85" alt="image" src="https://github.com/user-attachments/assets/d1c5b49d-4b41-4eb1-8c90-46e048751aab" />

### 19)	chown Command

The chown command is used to change ownership.
Syntax: chown owner_name file_name

<img width="487" height="167" alt="image" src="https://github.com/user-attachments/assets/5cc9017e-0db8-4b9b-8a60-6209b5bc4a1e" />


### 20)	make Command

The make command is used for building and maintaining group of program.
Syntax: make [-f makefile][options]…….[targets]….

<img width="361" height="43" alt="image" src="https://github.com/user-attachments/assets/5fcd922a-a324-4ce6-b977-81815ede8495" />

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.
Syntax: ifconfig[options][interface]

<img width="632" height="187" alt="image" src="https://github.com/user-attachments/assets/b93bce48-0a42-42fd-b7d6-f0f06e23c232" />

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.
Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

<img width="482" height="156" alt="image" src="https://github.com/user-attachments/assets/0972298a-ca0b-4e99-a91c-3cdf005336ae" />

### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.
Syntax: host <domain name> or <ip address>

<img width="505" height="245" alt="image" src="https://github.com/user-attachments/assets/854ce9be-a146-4742-a364-64110013d9c2" />

### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.
Syntax: gzip <file1> <file2> <file3>..

<img width="361" height="97" alt="image" src="https://github.com/user-attachments/assets/835a3a33-dc2d-4c37-8820-589c82ec62d0" />

### 25)	sort Command

The sort command is used to sort files in alphabetical order.
Syntax:sort <file name>

<img width="388" height="236" alt="image" src="https://github.com/user-attachments/assets/f4776a25-6b39-4c20-97b7-263b61140445" />

### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.
Syntax: cal


### 27)	clear Command

Linux clear command is used to clear the terminal screen.
Syntax: clear

<img width="352" height="66" alt="image" src="https://github.com/user-attachments/assets/e8f66119-e0f8-4153-add6-e87c05108ddd" />

### 28)	mail Command

The mail command is used to send emails from the command line.
Syntax: mail -s "Subject" <recipient address>

<img width="582" height="42" alt="image" src="https://github.com/user-attachments/assets/7a099c47-b12e-4086-9347-c6675ee94033" />

### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.
Syntax: df

<img width="622" height="302" alt="image" src="https://github.com/user-attachments/assets/952fe94b-a9be-4229-b71e-8b9bd98bc77d" />

### 30)	find Command

The find command is used to find a particular file within a directory.
Syntax: find.-name”*.pdf”

<img width="310" height="112" alt="image" src="https://github.com/user-attachments/assets/8e94c2ce-4710-457d-909c-f012f73ab71b" />

## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
