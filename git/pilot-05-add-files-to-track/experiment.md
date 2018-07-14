# **Add Files To Track**

# **Experiment**

1. ### Before you can commit your files or changes within existing files to the repo, you need to tell Git to track these files so that it can always follow its progress. The reason you need to tell Git to track these files is because sometimes you don't want Git to know about all the files that's currently in your directory. Sooner there will be a pilot where you would specifically tell Git not to track certain files by using a `.gitignore` file. 

2. ### Git only tracks the files you tell it to track. To track a file, you need to add that file to the **staging area** or **index**. You are telling Git to see the files that's in the **stage** just like the audience sees a performer on the theater stage. That's the reason it's been called the **staging area**. You are staging files so that they could be visible to Git. 

3. ### To add files to the **staging area** so Git could see and track it, you need to execute this command: `git add filename`. You can either add a single file: `git add filename` or multiple files: `git add filename1 filename2` or all the files in the **working directory**(directory where you currently modify): `git add *`. 

4. ### Create a Git repo as in **Git pilot-02** and setup configuration using either **Git pilot-03** or **Git pilot-04** as you desire. Let's assume you had turned an empty directory into a Git repo. At this very early stage, **working directory** is empty as it doesn't contain any saved version out of the local database. You just initialized the repo so there's no way it can contain any saved version in the local database. So create an example text file and name it "first.txt". To tell Git to add this file to the staging area so as to track it, execute this command: `git add first.txt`. Now this first.txt file is being tracked by Git. 

5. ### Create new directories "second" and "third" inside the **working directory**. Now you might think Git can see these two directories if you add them to the **staging area**. But in reality, Git doesn't see empty directories. So create two files inside the two directories and name them "second.txt" and "third.txt". To track all these newly created directories and files inside them, execute this command: `git add *`. This command tells Git to track all the files that's currently in the **working directory** which is not empty anymore. Now we have everything ready to save the first version of our **working directory** into **Git repo**. 

## **Reference**

[Pro Git]()

Source: Prometheus-books/Git/progit