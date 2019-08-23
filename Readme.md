# Simple Argument Parser (SAP)

A simple argument parser written for C/C++ CLI applications. It is written in C
such that both only-C applications and C++ applications can make use of it.

It is inspired by some basic functionality from [clap from Rust](https://clap.rs/)
in terms of the desired output, but is nowhere near as function-complete. I
only aim to properly implement in a reusable fashion the functionality I need
to use for my own projects.

I chose not to use getopt or any other similar options as I would like my projects
to be portable across as many platforms as possible.

## Compilation

To compile, simply run:

```make```

## Doxygen documentation

To generate documentation, enter the repository directory and run:

```doxygen Doxyfile```
