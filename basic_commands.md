# Basic Commands

* `uname`  system information

* `man`  man stand of manual
  * examples:
    * `man man`
    * `man ls`
    * `man cat`
* `cd` change directory
  * absolute path. start from root. for example `/home/amin/Documents/examples/`
  * relative path. start from current path. for example `./Documents/examples/`
* `type` information about command type. there are two types of commands in Linux, belong to Linux itself or third-party
  * examples:
    * `type node`
    * `type cd`
* `mkdir` make directory
  * examples:
    * `mkdir examples`
* `touch` create file
  * examples:
    * `touch file.txt`
* `rm` remove file or directory
  * examples:
    * `rm file.txt`
    * `rm -r examples`
* `ls` list directory content
* `cat` concatenate files and print on the standard output
  * examples:
    * `cat file1.txt file2.txt`
    * `cat file.txt -n` or `nl file.txt`
* `history` history of the used commands.
  * tip: each command has a number
    * `!554` 554 is number of the command. runs command number 554
    * `!!` runs last command
  * tip: Where is the history information stored? `/home/[user]/.base_history`