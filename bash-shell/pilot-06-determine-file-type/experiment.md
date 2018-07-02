# **Determine file's type**

## Shell commands like ls, cd are actually C programs integrated into the shell program to facilitate(make easy) common programmer tasks. There are many such commands integrated into bash shell. From this pilot onwards, we'll take a look at some of the most useful ones. 

# **Experiment**

1. ### To find the file's type of any file or directory, use the `file` command followed by the name of the "file" or "directory". For instance, create a basic text file and name it "somename.txt" and write something on it and save. Now type `file somename` to get the file type of this "somename.txt" file.  You should get an output that says "somename: ASCII text". ASCII(pronounced: as-key) is the most common text format and also the most efficient way to store text characters in a computer. 

2. ### To find the file's type of all the files and directories in a directory. Just execute this command: `file *` . The asterisk symbol `*` means give the file type of all the contents in the directory. Let's do an example. Change into this directory: `/bin` in Ubuntu. Execute: `file *`. The `/bin` folder is a system folder that contains most of the commands you've used so far in shell.

## **Reference**

[The Linux Command Line]()

Source: Prometheus-books/Shell/The_Linux_Command_Line


