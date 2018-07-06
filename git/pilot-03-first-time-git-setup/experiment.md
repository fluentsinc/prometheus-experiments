# **First Time Git Setup**

# **Experiment**

1. ### After you install Git in your operating system, you need to make a couple first time setup before you can use Git. 

2. ### First of all, you need to configure Git to use custom identity information for each **commit** such as author name and author email. Second of all, you need to understand that you can have different configurations for different setups. The common setups are: 1. you can have system-wide configurations for all users, 2. you can have user-wide configurations for a specific user and 3. you can have directory-specific configuration for a specific directory.

3. ### Let's skip system-wide configurations for now because we rarely ever use them. Let's do a user-wide configuration. This should be the first step you should do after you install Git. 

4. ### Execute these commands below to setup up your identity information, make sure you subsitute your username and email address in the appropriate fields: 

- `git config --global user.name "use your preferred user name here"`

- `git config --global user.email "use your preferred user email here"`

5. ### Now every time you **commit**, Git uses the above information for your commits for all the Git repos that you create with this user. 

## **Reference**

[Pro Git]()

Source: Prometheus-books/Git/progit