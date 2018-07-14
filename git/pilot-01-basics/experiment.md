# **Basics**

## Git is a version control system that records changes to a file or a set of files over time with the ability to recall specific earlier versions. 

## Git is also a distributed revision control system which is a form of version control system where the entire codebase(software code of a project) is found in each developer's computer. And each codebase in each developer's computer is a mirror of a remote hosted codebase which is usually hosted in git-hosting sites like github. 

## When a developer changes the codebase in his/her codebase and updates those changes to the remote hosted codebase, all the developers working on the codebase gets notified of the changes made. 

## So with Git, you can easily see the changes made over time. Revert(return back) the codebase to an earlier time if a developer screwed something up. Every developer could work on the codebase remotely without any dependence on other developers working on the same codebase.

# **Experiment**

1. ### Git first stores the changes to the local database. Only after that, you can upload the changes to the remote database for all the other developers to see. That's probably the first thing you need to get your head around. Local databases and remote databases sync with each other to catch up with the changes. 

2. ### In Git, there are three states that your files can be in: **Committed**, **Modified**, and **Staged**.

3. ### In Git, there are three places that your files can be in: **working tree** or **working directory**, **staging area** or **index** and **git directory**.

4. ### In Git, the changes made by you are saved to the database as a snapshot which is a version of all the files that exist at that point instead of saving individual changes. So Git saves all the files that have changed instead of saving individual differences like "D" changed into "A". Refer pdf-reader-page-no-8 for section "Snapshots, Not Differences" to know more about this.  

4. ### When you save your changes to the local database, the file's state is **Committed** because the file with the changes is committed(saved) to the local database which is actually inside the **git directory**.

5. ### When you change a file but don't save the change to the local database, it's state is **Modified**. And the file is in the **working tree** or **working directory** which is a checkout(get a saved version out of local or remote database) of one version out of all the versions of the files that are already saved to the local database. Here, the **modified** files are in **working directory** because you modified a version of files that have already been saved to the local database. 

6. ### When you modify files in your **working directory**, you may want to selectively save certain files or you may want to save all the files that have changed. We need to tell Git about what we're trying to do. Once we've made our choice, we need to tell Git to put certain modified files or all modified files in **staged** state. When files are in **staged** state, they are ready to be **committed**(saved) to the local database. **Staged** files are temporarily saved in the **staging area** which is inside the **git directory**. 

7. ### **Git directory**, **staging area** and **working directory** collectively make up what's called a **Git Repository**(repository means a place where you store valuable information) or **Git Repo** for short. 

8. ### Each version of files stored in a **git repo** is stored using a hash algorithm called "SHA-1". Hashing algorithms take files and create a hash value or message digest which is a hexadecimal(0-9 and a-f) string of characters of length 40. A hash value or message digest looks something like this: `d321db2e7ac2aee123205dd81b260c436c03068d`. Each hash value uniquely identifies a set of files. So if you add any change to a set of files, the hash value changes thus uniquely idenfying the new version. That's how Git knows when you modify files, the hash value changes thus letting Git know that there are changes in the files.  

9. ### Each version of files stored in a **git repo** is called a **commit**. Each commit has a hash value associated with it. Each commit also has a commit message, commit time/date, commit author and author's email associated with it. 

10. ### Always execute the Git commands after you change directory `cd` into the git repo.


## **Reference**

[Pro Git]()

Source: Prometheus-books/Git/progit