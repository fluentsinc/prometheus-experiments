# **Pathnames**

## **Pathnames** or **path** is a description that points to a location in a filesystem. A simple _**analogy**_ for a **path** could be an address to a location in the real world. In filesystems which usually have a lot of files and directories, the **pathname** or **path** helps you easily locate any files or directories.  

# **Experiments**

### **1.** Execute the `pwd` command to see a great example of a **pathname** or **path**. The output shows a **path** which points to your current working directory. 

### **2.** In Linux, a single forward slash `/` refers to the root directory. The root directory is a directory that contains all files and subdirectories in your computer. The root directory contains all the files that your computer has, from the boot files necessary to boot up your operating sytem to the directory that contains your favorite movies. 

### **3.** The **pathnames** are always in a tree structure. That is, just as a real world tree, the pathnames start with the "root" directory. Inside the root directory, you might have several subdirectories. Kinda like how in the real world, you have the root of a tree and as you go up the tree, you might find several branches. The subdirectories inside the root directory might have several subdirectories themselves. Again, similar to the real world tree where each branch has several other branches. 

### For example, `/user/fluents` is a pathname. The pathname started with the root directory symbolically represented as "/". Inside the "root" directory, there is a subdirectory named "user". Inside the "user" subdirectory, there is a directory named "fluents" where the pathname finally ends. `fluents` is the directory that the pathname `/user/fluents` was trying to locate. 

### Similarly, you could have a pathname that points to a file. The pathname `/user/fluents/fluents.sh` points to a file named "fluents.sh". 

### **4.** A pathname, for example `/user/fluents`, is always chained with a forward slash `/` to denote the hierarchy of directories, subdirectories and files. In other words, the first forward slash `/` in the pathname `/user/fluents` refers to the root directory. The second forward slash `/user/fluents` tells you to go inside the "user" directory to find a directory named "fluents". The second forward slash, in this example `/user/fluent.sh`,  could also tell you to go inside "user" directory to find a file. Files are always denoted with an extension(like: .js, .java, .sh) unlike directories.    

### **5.** The root directory is always referred to as the top level directory kinda like the top floor in a tall building. The subdirectories inside the root directory are referred to as "one level down" just like you would in a real building. The subdirectory inside one of the subdirectories inside the root directory is referred to as "two levels down" and so and so forth. Go back to experiment-#1, take a look at the **path** you got from `pwd`. Enter the names of "one level down" and "two levels down" directories into "master.md".      



## **Reference**

### [The Linux Command Line]()

### **Source:** Prometheus-books/Shell/The_Linux_Command_Line
