# **Initialize a Git Repo**

# **Experiment**

1. ### There are two ways to get a Git repo on your hands: 1. You can either turn a normal directory in your local machine into a Git repo. Or 2. You can clone an existing Git repo from somewhere else. 

2. ### In this pilot, we'll get to know how to do the former. We want to turn a local directory into a Git repo. 

3. ### First off, we need to create a directory that's going to be our project directory. `mkdir stars` creates a directory named "stars". Let's assume that's our project directory. But right now, it's just a normal directory without version control. In other words, it's just an ordinary directory without Git enabled on it. 

4. ### Do `cd stars` to get into the "stars" directory. Execute `git init` to turn this normal local directory into a Git repo. Once you execute this command, you can see a ".git" directory created on the project directory. This ".git" directory consists of the database where Git's going to save the **commits**. Since directories that start with a `.` are hidden directories, it won't be able to view this ".git" directory in Linux/Unix environments. Execute `ls -la` to see this hidden ".git" directory.

5. ### When we executed the `git init` command and created the ".git" directory, the normal local directory has been turned into a Git repo. Now with our example, we've initialized the "stars" directory into a Git repo. Likewise, the moement you delete the ".git" directory inside the "stars" Git repo, "stars" directory goes back to being a normal directory.  

## **Reference**

[Pro Git]()

Source: Prometheus-books/Git/proGit