# **Create a New Directory**

## So much of what you can do with a GUI(graphical user interface) can be done using a CLI(command line interface). The command we are going to see here will help you create directories so much faster than if you were to use a GUI version where you're clicking "new folder" with your mouse every single time. 

# **Experiment**

1. ### First, `pwd` to find your current working directory. Second, `ls` to list all the files and directories in that current working directory. 

2. ### Some commands take implicit(hidden, implied) arguments like `pwd` and `ls`. Some commands take explicit(clearly defined) arguments like `mkdir` command. The `mkdir` command creates a new directory and you need to provide a name or a list of names you want your directories to have after a space. So for instance, to create a directory named car, you would execute this command `mkdir car`. And to create three directories all at once, you would do `mkdir lexus porsche ferrari` to create three directories named "lexus", "porsche" and "ferrari". The newly created directory is not "Lexus", it's "lexus". Shell commands are case-sensitive. If you mean uppercase then you get uppercase and if you mean lowercase you get lowercase. 

3. ### To put everything together, implicit arguments are usually implied hence they are mostly empty. But for explicit arguments, the usual pattern is `command arguments`. For example, `mkdir car`. Here, "car" is the argument. 

4. ### The usual patterns for shell commands are:

 - `command` Eg. `pwd` 
 - `command -option` Eg. `ls -l` 
 - `command arguments -options` Eg. `mkdir cars -p` 
 - `command -options arguments` Eg. `mkdir -p cars` 

# **Command Line Jargons** (technical terms)

## **Absolute Pathnames**

- ### Pathnames are the routes you take along the **directory tree** to get to the directory or the file we want to use. The analogy(comparison to ease explanation) here is that of the real tree. Just as in a real tree where we can have branches, the **directory tree** also has branches. If we follow up the route from the root directory to the directory we want to use, then we say we have the **absolute pathname** to this directory we are interested in. For example, let's say there's a directory named "Secret" inside another directory named "Personal" and this "Personal" directory is itself inside the root directory. The **absolute pathname** to this "Secret" directory is the route we can follow from the root directory. So here, the **absolute pathname** is `/Personal/Secret`. See, we can also take the route from "Personal" directory to "Secret" directory. But in a **absolute pathname**, we always take the route along the root directory. 

## **Relative Pathnames**

- ### **Relative pathnames** are pathnames that don't follow the route from the root directory. They are usually pathnames that are relative to another directory. Mostly, they are relative to the **current working directory**. For example, in the above example, if our **current working directory** is `/Personal`. Then the **relative pathname** would be `./Secret`. Here the symbol `.` denotes the **current working directory**.  The `./` symbol before the **relative pathname** `./Secret` is implicit(implied) so it could be ignored. So the pathnmae `./Secret` is same as `Secret` if "Secret" directory is present in the **current working directory**.  

## **Reference**

[The Linux Command Line]()

Source: Prometheus-books/Shell/The_Linux_Command_Line

