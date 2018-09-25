# **List Files And Directories**

## The `ls` command lets you list out all the files and directories in the current working directory or in the directory of your choice. 

# **Experiments**

### **1.** The `ls` command lets you see all the files and directories inside the current working directory. Execute the following commands: 

### `cd` 

### `ls`

### The above commands should have listed out nothing since you didn't create any files in your home directory. 

### `cd /`

### The above command changes into the "root" direcotry. 

### `ls` 

### Now that we had changed the current working directory to the "root" directory, we would be able to see all the files and directories inside the "root" directory. 

### Let's try to explore the "root" directory. 

### `cd usr`

### `pwd`

### `ls`

### `cd sbin`

### `pwd` 

### `ls` 

### The above commands finally _**ended up**_ listing out the files and directories in the "sbin" directory.

### **2.** You can directly list out files and directories of a directory instead of changing into the directory by using `cd` everytime. But the important point to take away here is that, your current working directory did not change. Execute the following commands:

### `cd` 

### The above command takes you back to the logged-in user's home directory

### Now to directly list out the "sbin" directory in the path `/usr/sbin` in `experiment-#1`, execute the below command: 

### `ls /usr/sbin` 

### The above command lists out the "sbin" directory without changing the current working directory with `cd`. 

### `pwd`

### The above command verifies that your current working directory didn't change. It should be same as the your home directory, not "sbin" directory. 

## **Reference**

### [The Linux Command Line]()

### **Source:** Prometheus-books/Shell/The_Linux_Command_Line
