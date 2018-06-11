# **List Files and Directories**

## With a graphical user interface program such as file explorer in Windows, we can easily see the files and subdirectories available in a directory by simply clicking on the parent directory. Not so with a command line interface program like shell, as you're probably aware by now, we need to enter a certain command to be able to see the files and subdirectories available in a directory. 

# **Experiment**

1. ### Type: `ls` to see the files and directories in the current working directory. 

2. ### Type: `ls /movies` to see the files and directories in the **/movies** directory. So in general, the command is `ls /directoryname` where directory name is the directory where you're trying to see the file contents. 

3. ### Type: `ls -l` to see the files and directories and to reveal more informations such as directory attributes, size, etc. 

4. ### Type: `ls -a` to see all the files and directories including all the hidden files and directories. 

5. ### As a matter of fact, there are a lot of **options** you can use with the `ls` command and a number of different **arguments** you can act upon. Refer *pdf-reader-page-number: 47* to get the most common **options** you could use with `ls`.    

# **Command Line Jargons** (technical terms)

## **Options**

- ### A bash shell command can take many **options**. For example, `ls -l` and `ls -a`. In this example, `ls` is the shell command and `-a` is the option. A option always starts with a hyphen. A command could also take a long option in place of a option. For example, instead of `ls -a`, you could use `ls --all`. In this example, `-a` is the option and `--all` is the long option. Both of the **options** do the same job. It's just a matter of convenience. Refer *pdf-reader-page-number: 47* to get the most common **options** you could use with `ls`.


## **Arguments**

- ### A bash shell command can take several **arguments**. For example, `ls /movies /pictures`. In this example, `/movies` and `/pictures` are both arguments upon which the command `ls` acts. So the above example lists out files and directories present in the "movies" and "pictures" directories. **Arguments** are usually files and directories. If you leave the **arguments** empty, for most commands the argument by default is the current working directory. For example, `ls` command displays the files and directories in the **current working directory**. The argument is empty but since the default argument is the **current working directory**, the command executes.

## **Reference**

[The Linux Command Line]()

Source: Prometheus-books/Shell/The_Linux_Command_Line