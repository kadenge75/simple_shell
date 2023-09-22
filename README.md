# Simple Shell

## Description

Basic Shell is a UNIX command line interpretation developed as part of the ALX Software Engineering program. It provides a basic shell environment in which users can execute simple commands.


## Table of Contents

- [Getting Started](#getting-started)
- [Usage](#usage)
- [Built-in Commands](#built-in-commands)
- [Authors](#authors)
- 
## Getting Started

To get started with the Simple Shell, follow these steps:

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/kadenge75/simple_shell.git
   ```

2. Compile the shell using GCC:

   ```
   gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh
   ```

3. Run the shell:

   ```
   ./hsh
   ```

## Usage

Once you have the Simple Shell running, you can use it to execute various UNIX commands. Here are some basic examples:

```shell
$ ./hsh
($) /bin/ls
file1  file2  file3
($) echo "Hello, Simple Shell!"
Hello, Simple Shell!
($) exit
$
```

## Built-in Commands

The Simple Shell supports the following built-in commands:

- `exit`: Exits the shell.
- `env`: Displays the current environment variables.

## Authors

- Mike Kadenge
- Alexander Gichimu

## Copyright 
  -@kadenge & agichimu2023.AllrightsReserved.
