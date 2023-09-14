---
title: Navigating the File System in Bash
categories: bash
image: https://github.com/raidOffensiveTechnology/raidOffensiveTechnology.github.io/blob/main/assets/img/bash.png?raw=true
---
Commands you will learn:
- pwd
- ls
- cd

## PWD
To find out where we are in the command line, we run `pwd`.
`pwd` means: **P**rint **W**orking **D**irectory, this basically meanse it will tell us the **directory** we are **working** in.
On a macOS Computer, this command returns something like this:
```
/Users/<your name>
```
Everyone gets a different output because not everyone has the same username.

## LS
Now that we know where we are, let's find out what is in the **directory** we're **working** in. To do that, run: `ls`
The command output can look something like this.
```
Desktop      Documents    Downloads    exam2023.pdf meme.png
```
It will list all the files and **directories** in the **directory** we are **working** in.

## CD
Now that we know where we are, and what is around us, let's move into one of those **directories**. Let's move into the `Downloads` **directory**.
We would run: `cd Downloads`
This moves us into our desired **directory**.
To move back a **directory**, we would run: `cd ..`
Imagine we want to move back all the way into the home **directory**, we would run: `cd `.
> Make sure your command is `cd ` and not `cd`
{: .prompt-warning }
