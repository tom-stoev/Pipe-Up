# Pipe Up

This program functions as the pipe '|' operator in shells redirecting the output from
a previous process to the input of a following process. 

## Building

The program is built using the provided makefile and running "make". 

## Running

Sample Usage: 

./pipe ls cat wc 
```
performs ls | cat | wc
```

./pipe ls tail 

```
performs ls | tail 
```

The program needs at least one command. Will report error if no commands follow
or non existing commands are used as input. 

## Cleaning up

The binary files are cleaned up by running 'make clean'. 
