# linuxCommandUnderstand

## what  is linux?

linux is an operating system.mainly it is a kernel between hardware and software. created by linus torvalds in 1991.version released in 1994. free open source software(foss).linux has many types of distribution.example-ubuntu,kali linux,debian,centOS etc.

## why we learn linux?
runs on all types of hardware platform.known for being stable,reliable,and secure, and great for servers . linux is free and many software inside it is also free.

note: the kernel is the core 

LINUX KERNEL + APPS = DISTRIBUTION

MOST POPULAR: REDHAT AND UBUNTU

# most popular directories

/        KNOWN AS THE ROOT DIRECTORY

/BIN     BINARIES AND OTHER EXECUTABLE PROGRAMS RESIDE HERE 

/ETC     SYSTEM CONFIGURATION FILES

/HOME    HOME DIRECTORIES

/OPT     OPTIONAL OR THIRD PARTY SOFTWARE 

/TMP     TEMPORARY SPACE,TYPICALLY CLEARED ON REBOOT

/USR     USER RELATED PROGRAMS

/VAR     VARIABLE DATA,MOST NOTABLE LOG FILES

![image](https://github.com/Riyatomar14/linuxCommandUnderstand/assets/143107173/73897796-afd3-41e4-9c36-b21036e86185)

*ls --> list directory 

*cd --> change directory

note : when there are two many arguments like file name - human resources

cd argu1\ argu2\ argu3\ lastArgu/

cd human\ resources/

*cd .. --> to go back to directory

*pwd --> (print working directory) you know where you are currently present 

*cat --> content of particular file 

*clear --> after clear you still in current location 

*echo -->  a way to communicate with your Linux terminal. example - echo"hello"  .... it give hello

*touch --> to create a new file 

*exit --> exit from terminal

*mkdir --> make directory

note: you want to make two directory at one time 

mkdir angela cat 

*rmdir--> remove directory only if there are no file inside 

*rm -rf directoryname/ --> remove whole folder

*help cd ---> more detail about cd

*ls -a --> to see every hidden files or every single file 

*ls --color  --> colourized format 

*ls -d 

*ls -l -> you get a long directory with basic detail

note: when we apply , we get the file permissions which are used to  control who can read,write and execute a given file or directory.

*id -Gn --> which group are you in 

*ls -r --> reverse the order of files

*ls -t --> sort with respect to time

*type -a chmod --> to change file permission 

### how to change file permissions

UGOA --> U for users ,G for group ,O for other ,A for all

+-=  --> + to add permissions,- to subtract permissions, = set all

RWX  --> R for read , W for write ,X = execute 

*how to change read permission
![how to change read permission](https://github.com/Riyatomar14/linuxCommandUnderstand/assets/143107173/641ab7dc-53fd-4531-9f58-6958fcbe39aa)
*how to change read,write and execute permission
![how to change read,write and execute permission](https://github.com/Riyatomar14/linuxCommandUnderstand/assets/143107173/631ee2b1-523c-43fb-ac08-348090bb5207)


### help pages which exists as a shell built-ins 

#### to find help for ls command

type -a ls

#### to find help for echo command

type -a echo

### or help from man page (for which does not have shell built ins)

man ls

man echo 

# how to find the file 










