# **Bash Symbol - tilde**

##  In this pilot, we're going to take a look at the bash symbol tilde `~`. The symbol `~` is referred to as a tilde(pronounced til-day). 

# **Experiments**

### **1.** The tilde symbol `~` in bash refers to the currently logged-in user's home directory. Execute the following commands:

### `cd /` 

### The above command takes you to the root directory. We are going there just so we can set ourselves up. 

### `cd`

### The above command takes us back to the home directory of the currently logged-in user. 

### `cd /`

### Again we are going back to the root directory. 

### `cd ~`

### The above command `cd ~` again takes us back to the home directory of the currently logged-in user. The commands `cd` and `cd ~` both do the same thing. No matter where you are, they change the current working directory to the home directory of the currently logged-in user. 

### `pwd`

### The above command checks the current working directory. Enter the output into "master.md". 

### When we write bash scripts, we would find that the command `cd ~` is more valuable to us than the command `cd`. We know that both commands do the same thing but representation of something with a symbol is very convenient. The reason is because with a bash symbol like `~`, we can _**explicitly**_ and accurately define what we mean in a bash script. For example, let's just say that you want to get into a directory named "route" in your home directory from the root directory.

### `cd ~`

### The above command takes you to the home directory of the currently logged-in user. 

### `mkdir route`

### The above command creates a directory named "route". 

### `cd /`

### We went back to the root directory. Now what we want to do is to, get from the root directory to the route directory. 

### Inefficient way to do the above defined task is to execute the below commands:

### `cd` or `cd ~` 

### `cd route`

### Efficient way to do the above defined task is to execute the below command: 

### `cd ~/route`

### The above command uses an absolute pathname `~/route` with a bash symbol `~`. 

### `echo ~`

### Enter the output of the above command into "mater.md". 

### `cd /`

### The above command takes us back to the root directory again. 

### Now go to the "route" directory again but this time execute a command that uses an absolute pathname with the output of `echo ~`.


## **Reference**

### [The Linux Command Line]()

### **Source:** Pro-books/Shell/The_Linux_Command_Line
