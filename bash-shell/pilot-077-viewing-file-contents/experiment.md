# **Viewing file contents**

## There are several programs to view text files. Most of the configuration files in Linux are stored as human-readable text files. So there may come a time where you might want to see the configuration file associated with your server or reverse-proxy(server that stands before the main server which makes hackers think they are targeting the main server but in reality they're actually attacking the proxy server). 

### We're going to take a look at two such programs. If we had a text file with 100 pages, the`less` command outputs the text page by page while `cat` command outputs everything at once. 

# **Experiment**

1. ### As usual, the way to call command is `commandname filename`. So we can either execute `less filename` or `cat filename`. With `cat`, the program outputs all the pages to the screen and exits. With `less` though, the programs displays only a single page and lets you page through the whole file. So you can either press the "down arrow" to go to the next page or use the "up arrow" to go to the previous page. To finally exit the program, just type `q`. 

## **Reference**

[The Linux Command Line]()

Source: Prometheus-books/Shell/The_Linux_Command_Line




