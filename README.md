# Mini Unix Shell in C

## Overview
A simple Unix-like shell implemented in C - supports process creation, command parsing, and input/output redirection.

## Features
- Interactive command prompt
- Execution of external programs using fork/exec
- Command history tracking
- Support for command aliases

## Technical Highlights
- Use of POSIX system calls (fork, exec, wait)
- Manual memory management in C
- Modular design separating parsing, history, and alias handling

## How to Build and Run
```bash
gcc shellMain.c shell.c shellAliases.c shellHistory.c -o shell
./shell
```

## Notes
Originally developed as a coursework project at the University of Strathclyde
