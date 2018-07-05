# **Basics**

## Git is a version control system that records changes to a file or a set of files over time with the ability to recall specific earlier versions. 

## Git is also a distributed revision control system which is a form of version control system where the entire codebase(software code of a project) is found in each developer's computer. And each codebase in each developer's computer is a mirror of a remote hosted codebase which is usually hosted in git-hosting sites like github. 

## When a developer changes the codebase in his/her codebase and updates those changes to the remote hosted codebase, all the developers working on the codebase gets notified of the changes made. 

## So with Git, you can easily see the changes made over time. Revert the codebase to an earlier time if a developer screwed something up. Every developer could work on the codebase remotely without any dependence on other developers working on the same codebase.

# **Experiment**

1. ### Git first stores the changes to the local database. After that, you can upload the changes to the remote database for all the other developers to see. That's probably the first thing you need to get your head around. 

2. ### In Git, there are three states that your files can be in: **Committed**, **Modified**, and **Staged**.

3. ### Also in Git, there are three places that your files can be in: working tree or working directory, staging area or index and git directory. 

4. ### In Git, the changes made by you are saved to the database as a snapshot which is a version of all the files that exist at that point instead of saving individual changes. So Git saves all the files that changed instead of saving individual changes like "D" changed into "A". Refer pdf-reader-page-no-8 for section "Snapshots, Not Differences" to know more about this.  

4. ### When you save your changes to the local database, the file's state is **Committed** because the file with the changes is committed(saved) to the local database which is actually inside the **git directory**.

5. ### When you change a file but don't save the change to the local database, it's state is **Modified**. And the file is in the **working tree** or **working directory** which is a version of all the files that are still not saved to the local database. 

6. ### 


