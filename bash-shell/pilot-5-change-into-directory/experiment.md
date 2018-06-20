# **Change into Directory or Change the Current Working Directory**

## Whatever task we might set out to do, if we are not in the correct working directory, we won't be able to accomplish the task we've had set out. The analogy(comparison to ease explanation) we could think of is the scenario where someone is trying to get A from Z street when A is actually found in Y Street. If you don't change into the right directory where you need to execute some commands, the commands simply won't work because the files that the commands need to work on is somewhere else. 

# **Experiment**

1. ### The command to change the directory is `cd`. To change the **current working directory** to the currently logged in user's home directory, you would type `cd ~` Here, `~` the tilde symbol represents the pathname to the home directory of the logged in user. Type: `cd ~` and see the output of `pwd`

2. ### The `cd` command takes a **pathname** as an **argument**. That **pathname** could be either **absolute pathname** or **relative pathname**.

3. ### Create a directory named "pilotx-5": `mkdir pilotx-5` 

4. ### Change into this "pilotx-5" directory: `cd pilotx-5`

5. ### Create two directories inside "pilotx-5" directory: `mkdir first second`

6. ### Now if you `ls` the directory, it should show you two directories "first" and "second". Software developers mostly use **relative pathnames* to change into directory. And this is for a valid reason. The reason is, **relative pathnames** are accurate and shorter when compared to **absolute pathnames**. Let's do the task of getting into the "second" directory using both pathname types. 

7. ### First, let's do **relative pathname**. Now to change into the "second" directory, we can execute this command `cd second`. This works but only if your `pwd` shows you are inside the "pilotx-5" directory. Because only "pilotx-5" has a directory inside it named "second". 

8. ### Second, let's do **absolute pathname**. Now let's go back a directory. Typing `cd ..` takes you back up a directory taking you to the parent directory of your **current working directory**. Now if you `pwd`, you should get "pilotx-5" directory as your **current working directory**. Now type: `pwd` and copy the pathname you get from this command. Add `/second` to the end of this pathname. So your command should look like this: pathname from pwd + `/second`. For example, if your pwd is `/c/blah/bleh/`, you need to add `/second` to the end of the `pwd` output. So based on the example `pwd` output above, the command to change into the "second" directory is, `cd /c/blah/bleh/second`.   

9. ### As you see from the above examples, **absolute pathnames** are verbose(excessive use of words) and complex. Though these pathnames still have uses which won't get into now because it's kinda hangs on the advanced programming side. So for now, just get used to using **relative pathnames**. 

10. ### Now change into the "second" directory now and create a new directory named "third" inside it: 

- `cd second`
- `mkdir third`

11. ### Change into the "third" directory: `cd third` . Now let's go over a bunch of different tasks you might do with the `cd` command and some examples to reinforce(repeat what's necessary) the ideas that we've learned here.

12. ### At this point, your `pwd` should show `/c/your-main-project-folder/pilotx-5/second/third`. Now our little problem is to get back to the "pilotx-5" directory using **relative pathnames**. The answer is this, `cd ../..` This should take you back two directories up as the dot dot operator `..` goes back a directory. Since we've used the dot dot operator twice, this takes you up two directories. So the main point with all this is that, the dot dot **relative pathname** operator can be used to go back up any number of directories one might want to go up. 

13. ### Now that you are in the "pilotx-5" directory. Let's write a quick shell script to finish this pilot. Create a new file named "script.sh" inside the "pilotx-5" directory. Inside the "script.sh" file, write these lines:

```sh
pwd

cd first

pwd

cd ..

pwd

cd second 

pwd

cd third

pwd

cd fourth

pwd

cd ../..

pwd

```

14. ### Now the first time, you should execute these commands one by one to get a sense of what these commands are doing. After that, make sure you're on the "pilotx5-directory" and run the script using the following command: `bash script.sh`. Shell scripts can easily take thousands of lines of code so we usually put them in a shell script file that ends with ".sh" or .bash" file extension (.js, .png, .jpg, .java, .sh are all called file extensions, they let us know what type of file is being stored) so as not to type these commands one by one everytime.

15. ### In the "script.sh" file, I've purposefully included a common error most beginners make. That is, calling a command on a file or directory that does not exist. The line `cd fourth` gives you a "**bash: cd: fourth: No such file or directory**" error because "fourth" directory does not exist. We never created the "fourth" directory so calling a command on a non-existing file or directory would never work. 

16. ### The command `cd -` changes the working directory to the previous working directory. Make sure you're in "pilotx-5" directory, change into "second" directory. Now to go back to the "pilotx-5 directory, you could execute either `cd ..` or `cd -`. Both these commands do the same job here but the difference is `cd ..` just takes you back up a directory. But `cd -` takes you back to the previous working directory. To put in simple terms, `cd -` takes to the last `pwd`. For example, make sure you're in "second" directory, do `cd third` to get into "third" directory. Now do `cd ..` to go back up the directory to "second" directory. At this moment, if you wanted to go back to the "third" directory, you could do `cd -` instead of `cd third` because your last working directory was "third" directory. Refer *pdf-reader-page-number: 42* to see the most common shortcuts associated with `cd` command.


## **Reference**

[The Linux Command Line]()

Source: Prometheus-books/Shell/The_Linux_Command_Line







