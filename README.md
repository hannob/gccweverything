# gccweverything

clang has an option -Weverything to enable all warnings. gcc has no such option, so I
have created a simple shell script that takes all warnings from the help output.

Example usage:
```
gcc $(gccweverything) test.c
```
