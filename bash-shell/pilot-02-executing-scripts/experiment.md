# **Executing Bash Scripts**

## When you had executed built-in commands like `whoami`, `date` and `df` in **bash-shell/pilot-01**, you basically told bash shell that when you say "whoami" to the bash shell, execute the C program that prints out the name of the user currently logged into the computer. With "date" command, you told bash shell to execute the C program that prints out the current time and date. With "df" command, you told bash shell to execute the C program that prints out your hard drive's free space. The point here is that, you can see how the shell commands are in a way controlling a high level C language program. So we can actually say "bash" shell commands are a very high level language controlling a high level C language. 

## Now it's great to manually tell bash shell to do all these things one by one. But in reality, you wouldn't normally call a single bash shell command in real world applications. You wouldn't call the shell commands one by one as you did in **bash-shell/pilot-01**. In the real world, we create **bash scripts** that _**automates**_ some _**grunt work**_ not unlike a movie script. In a movie script, the director follows the script and tells a particular actor to say some line in a particular scene with a particular expression.  Likewise, when you write a **bash script**, you would tell high level programs to do something at some time in a definite order to automate some tasks.    

## When you hear "Automation", you would want to think about something that happens automatically with no human intervention. The grunt work that we want to automate with **bash scripts** could be as simple as deleting cache on our servers when the server is slow or _**provisioning**_ more servers when the website _**brings in**_ more traffic or converting file from one format to another to save space. To _**put things into perspective**_, we would usually use **bash scripts** to _**take care**_ of certain tasks so that a human doesn't need to resolve a problem everytime that it occurs. 

# **Experiments**

### **1.** Let's try to execute bash shell commands on a terminal one by one. This skill wouldn't be necessary when we build real world stuff because we would be using a bash script. _**Nonetheless**_, executing the bash shell on the terminal is such an essential skill because it greatly helps when you want to _**test out**_  the command and play around with them. Before you try to execute a bash shell command, make sure you're running a Linux or Unix operating system or a bash shell simulator like MINGW64 or a Linux subsystem like Kali or Ubuntu found in Windows 10 store. To execute a bash shell command on the terminal, open up the terminal and type the "command" and press enter. Execute the following bash built-in commands one by one to _**get a feel for**_ them: 

- ### `ps`

- ### `hostname`

- ### `cal` (only works on a real Linux OS or Linux Subsystem found in Windows 10 Store)

### **2.** There is a major difference between a general-purpose programming language like C , C++ or Java and a scripting language like bash script. We will _**get into**_ the difference when the times comes. For now, _**commit this to memory**_, a scripting language like bash script is very high level to a general purpose language because we can control programs of a general purpose programming language with a scripting language. Some languages are hybrid(Javascript and Python), they can be both a scripting language and a programming language.

### **3.** When you type some bash shell commands into a file that ends with an extension ".sh", you have what we're calling a "bash script".  Write these commands into a file named "movie.sh":

### `date`
### `hostname`
### `whoami`

### Now the bash script "movie.sh" contains three shell commands written in a order. When you execute the "bash script", the commands are executed in the order that the commands appear in the bash script file. For "movie.sh", the "date" command is executed first, the "hostname" command" second and then the "whoami" command. 

### **4.** To execute the bash script "movie.sh", we first need to tell bash shell where the file is. We will use a shell command called `cd` to accomplish that. For now, don't worry about what this `cd` command does. Just focus on executing the bash script. First, you need to put the "movie.sh" file into the pilot-02 folder inside `adventurist/bash-shell/`. Then, enter this command into your terminal: 

### `cd bash-shell/pilot-02` 

### Again, don't worry about what this command does. In the next few pilots, you'll learn a great deal about the "cd" command. 

### Now to execute the bash script "movie.sh", execute this command into your terminal:

### `bash movie.sh`

### You should've gotten a output where the first command "date" in the bash script outputs the current date and time, the second command "hostname" outputs the name of the host computer and the "whoami" command outputs the user currently logged in. 

### **4.** The bash shell has its own **scripting language** with its own syntax. The bash script we've created in "movie.sh" shows a very basic syntax as an example. We will look into the more advanced syntax of bash shell in the upcoming pilots.

## **Reference**

### [The Linux Command Line]()

### **Source:** Prometheus-books/Shell/The_Linux_Command_Line
