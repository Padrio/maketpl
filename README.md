# Makefile Template with automatic Help

While decluttering my project directory I found this template which have been created by someone else. I uploaded it here to share it with some of you and to find it in case it's needed for a project again.

## Description

This template automatically generates a help command which reads itself and generates a colored information page containing all targets and a description. An picture can be found below at the example section.

## Example

The template searches for comments right before a target definition. The comment **must** begin with two "Number signs" (#), for example:

```makefile
## This target builds the project
build:
  echo "Starting to build..."
```

Which would equal to the following when executing the default target by typing `make` or running the `make help` target directly.  
![Executed Makefile Help Target Example](https://github.com/padrio/maketpl/raw/master/.github/example.png "Executed Makefile Help Target Example")
