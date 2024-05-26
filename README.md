# shellScripts
My shell scripts

## Basic commands and info to know

### Unconditional command execution
whoami; pwd;

### Conditional command execution
1. && (If first one fails, seconds ddoesn't get executed)
    ls && pwd
2. || (If first one fails , second gets excuted.)
    foo || pwd


### replacement using carrot operator
** if uou want to replace a word or phrase in a command last run

ls -lrt /usr/johndoe

^johndoe^jill

### Run the last command as root/privileged user

sudo !!

not just sudo, you can insert anything before the last command using this command.

### Playing with date command

date +%R 24 hr format current time
date +%F date with yyyy-mm-dd format
date +%D date with mm/dd/yy format
