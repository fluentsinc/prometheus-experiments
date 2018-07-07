# **Set configuration for a specific repository**

# **Experiment**

1. ### Sometimes we might wanna have directory-specific configuration that only affects a specific directory. This is different from user-specific configuration that works for all the repos created by the user that uses the configuration. With directory-specific, the configuration works only inside that specific repo. 

2. ### You can pretty much use the same config commands as user-specific configuration without using the `--global` option. So to enable directory-specific username and email address, `cd` into the specific repo and execute these commands: 

- `git config user.name "use your preferred user name here"`

- `git config user.email "use your preferred user email here"`

3. ### Now Git uses the directory-specific configuration instead of the user-specific configuration inside this specific Git repo. 



## **Reference**

[Pro Git]()

Source: Prometheus-books/Git/progit