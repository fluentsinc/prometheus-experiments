# **Create Directory** 

# **Experiments**

### **1.** To create a new directory, type in `mkdir`, leave a space, enter the name of the directory that you want to create. Execute the following commands: 

### `cd` 

### The above command makes sure that you're on the home directory. 

### `mkdir first`

### The above command creates a directory with the name "first". 

### `ls` 

### Using `ls` to make sure that the "first" directory was in fact created. 

### **2.** You can also create a new directory by just specifying the pathname instead of changing the current working directory first. 

### `cd first`

### The above command changes the current working directory to the "first" directory you had created earlier. 

### `mkdir first-child`

### The above command creates a new directory named "first-child" inside the current working directory which happens to be the "first" directory. 

### `cd`

### The above command changes the current working directory from "first" directory to the current logged-in user's home directory. 

### Now `ls` should show you the "first" directory. 

### The command that follow creates a "second-child" inside the "first" directory without changing the current working directory. 

### `mkdir first/second-child`

### In the above command, `first/second-child` is the pathname that tells `mkdir` command to create a "second-child" directory inside the "first" directory. 



## **Reference**

### [The Linux Command Line]()

### **Source:** Prometheus-books/Shell/The_Linux_Command_Line
