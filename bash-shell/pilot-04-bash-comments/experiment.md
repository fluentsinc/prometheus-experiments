# **Bash Comments**

## Comments are texts that you write in your script to help everyone understand what's going on in your code. When you use a comment inside a script, the shell doesn't execute the comments as it's executing the commands because shell knows that it's a comment and that it's mainly there for the programmer to understand the code better when he reviews it again a couple months or weeks from now. 

# **Experiments**

### **1.** To execute a bash comment, use a `#`hash sign before the text that explains what's going on in your script. Execute the below commands into a file named "comment.sh" and execute "comment.sh": 

### `# we run ps command to see currently running processes`

### `ps`

### `# we run date command to print out current date and time`

### `date`

### **2.** You could also use the comments alongside the shell commands. For example, execute this code `echo breeze # echoed the word breeze` to only output "breeze". When bash shell sees the "#" sign it knows that what about to follow the "#" sign is a comment left by the programmer to understand his/her code.  

### **3.** When you use comments, bash shell never prints out anything to the terminal screen unlike `echo`. Comments are a great way to document what's happening in your code thus helping you understand what you did a long while back. The `echo` command is a great way to log what's happening in your code as the script is running. 


## **Reference**

### [The Linux Command Line]()

### **Source:** Prometheus-books/Shell/The_Linux_Command_Line
