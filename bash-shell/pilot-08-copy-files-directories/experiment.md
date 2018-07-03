# **Copy files and directories**

## This pilot starts the series of pilots that highlight some of the most common and frequently used bash shell commands that you need to know starting with the copy command `cp`, cut and paste command or move command `mv`, rename command `mv` and remove command `rm`. 

### Why use command-line programs like this when you could just use a file manager like file explorer in Windows or finder in Mac? The answer is power and flexibility. You can easily do simple tasks with a graphical file manager but you need to master command-line programs to be able to do complex file manipulations.


# **Experiment**

1. ### The copy command `cp` has this pattern: `cp filename destination`. The central idea is that, you first specify the file you want to copy. And then, you would specify the path you want the file to be copied to. So following this idea, create a playground directory and call it "play". This folder is where we're going to play with the `cp` command to get used to it. Inside this "play" directory, create two directories "source" and "destination" and a file named "src.txt". Now we need to get this "src.txt" into the "source" directory. The command for that is `cp src.txt source`. 

2. ### To copy multiple files, the patter is `cp file1 file2 destination`. 

3. ### Now to copy this "source" directory into destination directory, try this command `cp -r source destination`. Here, the option `-r` is necessary to copy directories, it tells the `cp` command to recursively(like a domino falling, first one hits the second one and second one hits the third one and so on and so forth) copy all the contents of the directory. So the option `-r` tells `cp` to copy all the files inside "source". And if "source" has any directories, copy all the contents in those directories too and do this recursively until there are no more files left. For example, the command `cp -r source destination` recursively copies "source" directory into "destination" directory. 
 
3. ### Refer pdf-reader-page-no. 61 for a complete list of **options** available for `cp` command and the examples with the `cp` command. 

## **Reference**

[The Linux Command Line]()

Source: Prometheus-books/Shell/The_Linux_Command_Line
