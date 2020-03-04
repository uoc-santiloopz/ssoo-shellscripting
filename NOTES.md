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

## I/O
The metacharacter `<` allows us to redirect the standard in to a file; also, the metacharacter `>` allows us to redirect the standard out to a file. The `>>` metacharacter adds the stdout to a pointed file.