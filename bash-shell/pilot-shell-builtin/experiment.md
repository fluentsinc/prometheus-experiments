### **2.** Execute the following commands: 

### `man cd`

### Enter the output of the above command into "master.md". The output tells you "no manual entry for cd" because `cd` is a **shell builtin**. 

### When we say "shell builtin", we mean C programs that are integrated into shell itself. In `bash-shell/pilot-01`, experiment #2, we referred to a "shell.c" program. This is the shell program that receives the commands you enter into your "terminal emulator".  When the "shell.c" program receives the command, it will look up if it knows a C program with that command name. If "shell.c" finds a command,  it will execute the command's C program. Commands like these that "shell.c" looks up and executes are referred to as "coreutils" short for "core utilities. 