# Linux-Basic-Shell
System:

This is the basic shell made by me by using C language. It performs 3
basic internal commands and 5 external commands of linux/unix based
system. Each of the external commands is handled by a different c file
which uses fork, exec, wait function(pthread and system) to execute the
command. Internal command is defined inside Shell.c .

Internal Commands:

pwd:

pwd command line options:
1. pwd -L : Print the names the current working directory
2. pwd -P : Display the physical current working directory

cd:

cd command line options:
1. cd .. : print the names the current working directory
2. cd / : this command is used to change directory to the root
directory

echo:

echo command line options:
1. echo -n : do not print trailing newline
2. echo —help : print all details about echo command

External Commands:

mkdir:

mkdir command line options:
1. mkdir -p : no error if existing, make parent directories as needed
2. mkdir —help : print all details about mkdir command

rm:

rm command line options:
1. rm -i : Request confirmation before attempting to remove each file
2. rm -d : Attempt to remove directories as well as other types of
files

cat:

cat command line options:
1. cat -n : Number the output lines, starting at 1
2. cat -e : display a dollar sign (‘$’) at the end of each line

ls:

ls command line options:
1. ls -1 : Force output to be one entry per line
2. ls -m : fill width with a comma separated list of entries

date:

date command line options:
1. date -u : print or set Coordinated Universal Time (UTC)
2. date -R : Use RFC 2822 date and time output format
 ( Example: Mon, 18 May 2016 05:39:16 -0600 )


Assumptions:
One assumption I have taken that user enters at least one space after
every command. No two commands can be given in a single line. Only
1 command can be given in a single line.
