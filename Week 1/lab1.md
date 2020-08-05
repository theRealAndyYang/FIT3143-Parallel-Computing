# Finding Help

## Task 1.a

man . . . . . . . . . . . . . . . . . Find and display online help page

which . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . Locate commands


## Task 1.b

man ssh


## Task 1.c

man [OPTION]... [COMMAND NAME]...

## Task 1.d

http://linuxcommand.org/

https://www.geeksforgeeks.org/

https://www.computerhope.com/unix/uhelp.htm

# File and Directory Manipulation

## Task 2.a

mkdir . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . Make directory
rmdir . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .Remove directory


## Task 2.b

touch [filename]



Users and Access Control

## Task 3.a

useradd [options] username
usermod -a -G groupname username


## Task 3.b

chmod go-rwx directoryname


## Task 3.c

Sets permissions so that, (U)ser / owner can read, can write and can execute. (G)roup can read, can write and can execute. (O)thers can read, can't write but can execute.


## Task 3.d

chmod +x [filename] to allow executable permissions.

chmod -wx [filename] to take our write and executable permissions.


## Task 3.e

ls -l [filename]


## Task 3.f

ls -l /name/subname/othersubname


# Linux Shell

## Task 4.a

bash


## Task 4.b

Up arrow key


## Task 4.c

tab


## Task 4.d

echo $PATH


## Task 4.e

alias [-p] [name[=value] …]


## Task 4.f

which [filename1] [filename2] …

“which” is used to locate the executable file associated with the given command by searching it in the path environment variable. Return 0 if found and executable, 1 if does not exist and executable, 3 if an invalid option is specified


## Task 4.g

[compiler name] ./[filename]



## Task 4.h

Usually the the current directory is not in $PATH


## Task 4.i

cat [filename]


## Task 4.j

find .-type f -name “*.html”


## Task 4.k

ls [directory]
./ [filename]


# Networking

## Task 5.a

IP address: 10.0.2.15
Hardware address: 08:00:27:02:8a:40
Netmask: 255.255.255.0


## Task 5.b

It allows mapping of hostnames or domain names to IP addresses.


## Task 5.c

It is a resolver configuration file that configures DNS name servers.


## Task 5.d

netstat -nr

Destination     Gateway         Genmask         Flags   MSS Window  irtt 	Iface
0.0.0.0         	10.0.2.2        	0.0.0.0         	UG        0 	0          0 	enp0s3


# Programming Tools

## Task 6.a

apt-cache search gcc



## Task 6.b

apt-cache search open mpi
