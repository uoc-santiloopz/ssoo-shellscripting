# NOTES


## PERMISSIONS
To see the permissions of a file, do it with the command `ll`.

`lrwxrwxrwx`

The first letter is the type of file:
* - -> normal
* d -> directory
* l -> link

Then permissions of user, group and all

## SOME LISTING FILE COMMAND TRICKS
* \*: represents any character sequence. `ls /bin/l*`
* ?: represents any single cheracter. `ls /bin/l???n`
* [ ]: represents a character within a range. `ls /bin/[aeiou]*[a-f]`

## PROCESSES
The command `ps` informs on all the processes existing on the current window, it can be parametrized to informa about the processes of a certain user with `-u`.

## I/O
The metacharacter `<` allows us to redirect the standard in to a file; also, the metacharacter `>` allows us to redirect the standard out to a file. The `>>` metacharacter adds the stdout to a pointed file.


## How would you check all the variables currently defined?
With the `set` command.

## How to redirect the stderr?
With the metacharacter '2>'.