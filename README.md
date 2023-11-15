## hsh

A simple shell written in C by Raymond Enokela.

### Requirements

* Ubuntu 20.04 LTS
* gcc
* Betty style

### Usage

To compile the shell, run the following command:

```
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh
```

To run the shell in interactive mode, simply run the following command:

```
./hsh


To run the shell in non-interactive mode, pipe the commands that you want to execute to the shell. For example, to list the contents of the current directory, you would run the following command:


echo "/bin/ls" | ./hsh
```

### Testing

To test the shell, you can run the following commands:

```
Interactive mode:

./hsh

($) /bin/ls
hsh main.c shell.c

($)
($) exit

Non-interactive mode:

echo "/bin/ls" | ./hsh

$ cat test_ls_2
/bin/ls
/bin/ls

$
$ cat test_ls_2 | ./hsh
hsh main.c shell.c test_ls_2
hsh main.c shell.c test_ls_2
```

### Author

Raymond Enokela and Akanni Ismail
```
